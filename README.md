# School_District_Analysis

## Overview of the School District Analysis:
Maria had requested an school district analysis based on school type, total students, total school budget, per student budget, average scores, passing percentage, and spending ranges. After the code was executed through Python DataFrame, Jupyter Notebook, the school board had notified Maria that some 9th grade students from Thomas High School appear to have academic dishonesty. Therefore, in this project, we will remove all Thomas High School 9th graders’ score results to make sure the analysis is accurate. At the end of this project, we will perform the school district analysis.

## Results:
### District Summary
After removing Thomas High School's students' math and reading scores, we can see that the average math score and average reading score for both charter and district have no impact; the passing percentage for district has no impact as well. However, the passing percentages for charter were affected. The result for charter's passing math percentage has dropped 4% (from 94% to 90%); the passing reading percentage has dropped 4% (from 97% to 93%); the overall passing percentage has dropped 3% (from 90% to 87%).
Please see Figure 1 and 2 for details:
![with_t_district.pgn](Resources/with_t_district.pgn)
![without_t_district.pgn](Resources/without_t_district.pgn)

### School Summary:
The results for the rest 14 schools remain the same in the school summary. The average math score and the average reading score for Thomas High School have dropped less than 0.1%. The major impacts for Thomas High School are passing math percentage, passing reading percentage, and overall passing percentage:
- Passing math percentage has dropped from 93% to 67%
- Passing reading percentage has dropped from 97% to 70%
- Overall passing percentage has dropped from 91% to 65%
Pleas see Figure 3 and 4 for details:
![with_t_school.pgn](Resources/with_t_school.pgn)
![without_t_school.pgn](Resources/without_t_school.pgn)
We've set the passing grade to 70, after removing the 9th graders' score result for Thomas High School, we can see that the passing percentage dropped significantly. So that, we can conclude that the 9th graders' scores are the major contributors for Thomas High School's passing rate, which they have received higher scores than other grades in Thomas High School.

### School Spending / School Size

The impact for School Spending and School Size are tiny. After we round the average scores and passing percentages, the result is the same for with and without Thomas High School's 9th graders' scores. We took a closer look at both results for School Spending and School size, we can see that the difference between these two results are less than 0.1%. The reason for this is because we have a large data set, and the 9th grade from Thomas High School is a small portion of the data so that removing their grade in this whole large data would result tiny impact.

## Summary:
At the end, we conculde that the major impact for replacing Thomas High School 9th grade's math and reading scores are:
- The Passing math percentage for Thomas High School (dropped from 93% to 67%)
- The Passing reading percentage for Thomas High School (dropped from 97% to 70%)
- The Overall passing percentage for Thomas High School (dropped from 91% to 65%)
- Thomas High School was ranked at the second place for the overall passing percentage among the top 5 schools, and after removing the reading and math score for Thomas High School, it was no long top 5 schools.

