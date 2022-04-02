# Written Analysis: School District Analysis
> Analyzing the scores for the school board using Pandas.

## Table of Contents
* [Overview of the project](#overview-of-the-project)
* [Results](#results)
* [Summary](#summary)


## Overview of the project
The purpose of this project is to analyze the test results for about fifteen different schools.The main analysis is focused on the performance of reading and math scores for all schools. After the school board reviewed all the data, it was determined that the data for Thomas High School's ninth grade class was compromised. The school board wants the data for them removed and then analyse the overall results again for a fair review. This project uses Pandas library to modify the data into tables and summarize the overall district and school metrics.


## Results

Below are the snapshots of the overall results of this analysis.


* District Summary<br />
![District Summary](./img/img_1.PNG)

* School Summary with ninth graders<br />
![School Summary](./img/img_2.PNG)

* School Summary after removing the ninth graders<br />
![School Summary](./img/img_3.PNG)

* Spending Summary<br />
![Spending Summary](./img/img_4.PNG)

* School Size Summary<br />
![School Size Summary](./img/img_5.PNG)

* School Type Summary<br />
![School Type Summary](./img/img_6.PNG)

* Top Five Schools<br />
![Top Five](./img/img_7.PNG)

* Bottom Five Schools<br />
![Bottom Five](./img/img_8.PNG)


**1. How is the district summary affected?**<br />
* The overall difference in scores was less than 1%, when we removed less than 500 test scores on the 40,000 student data set.<br />
  The percentage of Math decreased from 75% to 74.8% and the overall passing went down to 64.9% from 65%. 
  
**Original Disrict Summary**<br />

![Original district](./img/img_9.PNG)

**Adjusted Disrict Summary**<br />

![Adjusted district](./img/img_1.PNG)


**2. How is the school summary affected?**<br />
* Removing the ninth graders of the Thomas High School from the original data set had a huge impact on the overall passing rates numbers, with a drop to 65% as compared to a whooping 91%,in the original analysis.

 
**Original School Summary**<br />

![Original school](./img/img_10.PNG)

**Adjusted School Summary**<br />

![Adjusted school](./img/img_11.PNG)


**3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**<br />
* Replacing the data from the ninth graders's math and reading scores has no impact on other schools data. In the original analysis, the overall passing for Thomas High School landed at 91% whereas when the data was removed and adjusted, the overall performance of Thomas High School decreased to 65%. 


**4. How does replacing the ninth-grade scores affect the following:**<br />
* Math and reading scores by grade.<br />
  - Thomas High School had and average of 83.6 in math and 83.7 in reading for the 9th graders , in the original analysis. Now, these scores have been replaced with NaN and looks as below

![NaN](./img/img_12.PNG)

![NaN](./img/img_13.PNG)

![NaN](./img/img_14.PNG)

* Scores by school spending.<br />
  - There was very little to no impact on spendings by changing the 9th grade scores. Thomas High School falls under the $630 to $644/student spending range.


* Scores by school size and school type<br />
  - There was very little to no impact on the scores based on the school type or size.The numbers will be the same if converted to whole numbers. Thomas High School falls under the Charter School type and is defined as a medium sized school.

**Original Scores by School size and type**<br />
![original school size type](./img/img_15.png)


**Adjusted Scores by School size and type**<br />
![adjusted school size type](./img/img_16.png)


## Summary

Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are as below.<br />

   - Thomas High School's ranking dropped.
   - The overall passing rate changed.
   - The district as a whole also has its average math and reading scores decreased due to the decrease in the averages for the Thomas High School.
   - The data at the grade level now displays as NaN in reports for the 9th graders of Thomas High School.
 


