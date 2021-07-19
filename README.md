# School District Analysis

## Overview Of This Project
    - This project contains the data of different schools and students data and their budget and scores.

### Purpose 
      - The Purpose of this project is to analyze the data of per school summary of data like average math and reading scores,overall percentage scores and Thomas high school summary.
## School District  Result
       The Results of School District can be discussed as following:
         * In District Summary we merge the school data and student data to school complete   
           data df.After that we did analysis on top of school complete df.we calculate average math,reading scores and percentages of math and reading and overall percentage. The overall percentage in district summary is 64.9 as shown in the image below.
         * In School Summary df we calculate the average math & reading scores per each school  
           level and also percentages of math and reading & overall percentages per school level as we can see from the below image.
         * In School Summary after analysing  the Per schooanl level, for Thomas high school  
           the 9th grade scores are not correct,so we excluded the 9th grade scores and calculate the averages and percentages as mentioned in the above step the difference we see is the scores of math and readings are increased and also the overall percentage of Thomas High school changed to 90.630324 approximately.

         * By replacing the ninth grade scores the following things are affected. we will
           discuus in detail:      
                - The ninth grade math and reading scores are replaced with Nan/null value, 
                   for remaining grades the scores remains same. 
                - Before formatting the scores differ in decimal values for $630-644 spending 
                  range. After formatting the scores remains same even 9th grade scores are 
                  replaced.
                - Before formatting the scores are differ in decimal values for medium       
                  school range(1000-2000). But after formatting the scores by school size remains same after replacing 9th grade scores.
                - The scores by school type also remains same after formatting even  
                  9th grade scores are replaced, before formatting the scores are differ by decimal places for  charter school type.           

## School District Summary
    The main changes we observed after changing the math & reading scores for 9th grade are Average reading score ,average math score,% math passing,% reading passing,% overall Passing values are changed little bit by decimal values in Per school summary df for Thomas High School.And also observed little bit decimal value changes in different df's like  math & reading scores by grade,scores by spending range,scores by school size,scores by school type.