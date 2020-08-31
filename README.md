# School District Analysis

## Challenge Overview

Maria has given you the task of analyzing the school district data after realizing that grades of ninth graders at Thomas High School have been changed. The following need to be analyzed:

1. How is the district summary affected?
2. How is the school summary affected?
3. How does replacing the ninth graders' math and reading scores affect Thomas High School's performance, relative to the other schools?
4. How does replacing the ninth-grade scores affect the Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size and Scores by School Type?

## Challenge Summary
The analysis of the school district show that:

- Based on school district analysis, the number of schools, total students and budget remains unaffected
  - The average math score decreases by 0.1 from 79 to 78.9
  - The average reading score remains relatively unchanged at 81.9
  - The % of students passing math goes down by 1% frm 75 to 74
  - The % of students passing reading goes down by 1% from 86% to 85%
  - The overall passing percentage in both math and reading goes down by 1% from 65% to 64%

- School summary for all schools except Thomas High School remain unaffected.
  - For Thomas High School, the following changes occur due to the change in the reading and math scores:
    - The average math score decreases by 0.1 from 83.4 to 83.3
    - The average reading increases by 0.04 from 83.85 to 83.89
    - The % of students passing math goes down from 93.3% to 66.9%
    - The % of students passing reading goes down from 97.3% to 69.7%
    - The overall passing percentage in both math and reading goes down from 90.9% to 65.1%

- Based on the drop in the passing percentage, Thomas High School drops in position from being the no. 2 school to no. 8 school in the list
 
- Math and reading scores by grade remove unchanged for all schools except for Thomas High School.
- For Thomas High School, the math and reading scores remain unchanged for grades 10th, 11th, and 12th. For grade 9th, there is no data to report (NaN)
- The % of students passing math, reading, and both math and reading goes down for schools spending between $630 - 644. For the other spending ranges, the scores and % of students passing remain unchanged.
  - The % of students passing math goes down from 73% to 67%.
  - The % of students passing reading goes down from 84% to 77%
  - The % of students passing both math and reading goes down from 63% to 56%
- Based on school size, the % of students passing math, reading, and both and reading goes down for Medium sized schools. The reading scores and % of students passing remain unchanges for small and large type schools
  - The % of students passing math goes down from 94% to 88%.
  - The % of students passing reading goes down from 97% to 91%
  - The % of students passing both math and reading goes down from 91% to 85%   
- Based on school type, the % of students passing math, reading, and both and reading goes down for Charter schools. The reading scores and % of students passing remain unchanges for District schools
  - The % of students passing math goes down from 94% to 90%.
  - The % of students passing reading goes down from 97% to 93%
  - The % of students passing both math and reading goes down from 90% to 87%
