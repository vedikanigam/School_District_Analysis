# School_District_Analysis

## Overview of School District Analysis
In this project, we are helping Chief Data Scientist at City School District Ms. Maria in preparing an analysis of standardized test scores for schools in the city. This analysis will not include reading and math scores for ninth graders at Thomas High School as the csv data file shows evidence of dishonesty. Using Python, we will analyze the data to showcase trends in school performance. 

### Purpose
The purpose of the analysis is to provide insights about performance trends to assist the school board in making decisions about school budgets and priorities. We will create a district wide summary and a school summary which will inculde total budget, per student budget, average math score, average reading score, percentage of students passing math, percentage of students passing reading, and percentage of students passing both math and reading. Furthermore, we will provide insights about math and reading scores by grade, scores by school spending, school size, and school type. This summary has changed from the original summary as we have removed math and reading scores for ninth graders at Thomas High School.  

## School District Analysis Results

- **District Summary** -
Since, we have removed math and reading scores for ninth graders but total number of students remains the same, the average math and reading score, percentage of students passing math, reading, and both math and reading, has reduced but this change is almost negligible. For example the percentage of overall passing has reduced from 65 to 64.9. See image below-

![Original District Summary](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/ooriginal_district_summary.png)

![Revised Summary](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/district_summary.png)


- **School Summary** -
In comparison to the district summary, the school summary changes significantly for Thomas High School after not including math and reading scores for ninth grade. For example the overall passing percentage drops to approximately 65% from 90.9%. The numbers for other schools stay the same in this revised summary.
See image below-
 
![Original School Summary](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/original_school_summary.png)

![Revised School Summary](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/revised_school_summary.png)

- **Thomas High School’s performance relative to the other schools after replacing the ninth graders' math and reading scores** -
The position of Thomas High School in top schools does not change after replacing the ninth graders' math and reading scores. It stays at number two even after revisions are done to the original file. See image below - 

![Original Top Schools](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/original_top_schools.png)

![Revised Top Schools](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/revised_top_schools.png)

- **Math and Reading scores by grade** -
There is no change in math and reading scores except the ninth grade scores are shown as NaN in the revised code. See image below-

![Revised Math and Reading Scores](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/revised_mathscores.png)

- **Scores by school spending** -
There is very slight change (in decimals) in scores in the spending category $630-644. After rounding off the numbers, there is no change. See image below

![Original Spending Summary](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/original_spendingsummary.png)

![Revised Spending Summary](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/revised_spendingsummary.png)

- **Scores by school size** -
Again, there is negligible change in scores in the Medium school category with total students between 1000 and 2000. After rounding off the numbers, thereis no change. See image below

![Original School Size](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/original_schoolsize.png)

![Revised School Size](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/revised_schoolsize.png)

- **Scores by school type** -
Again, there is almost no change in scores in the school type category -Charter . After rounding off the numbers, thereis no change. See image below -

![Original School Type](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/original_schooltype.png)


![Revised School Type](https://github.com/vedikanigam/School_District_Analysis/blob/main/Resources/revised_schooltype.png)

## Summary
After replacing math and reading score of ninth graders from Thomas High School, most signicant change was in the school summary for Thomas High School. The percentage of students passing math dropped to 66.9% from 93.3%. The percentage of students passing reading dropped to 69.6% from 97.3%. The percentage of overall passing dropped to 65% from 90.9%

In the district summary, the changes are minor. The percentage passing math drops to 74.8% from 75%. The percentage passing reading drops to 85.7% from 86%. The overall passing percentage drops to 64.9% from 65%.

There is no change in the position of Thomas High School among best performing schools.

There is no change in the scores when the schools are organized based on spending ranges, school size, and school type.
