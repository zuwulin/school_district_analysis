# School District Analysis

## Overview of Analysis
The current project was requested by a district school board overseeing 15 high school bodies to evaluate current fund allocation efficiency and make adjustments to each respective school's budget, if needed.

### Purpose
The purpose of the current analysis was, first, to examine the overall performance trends across all 15 high schools within the district. Following the initial analysis, a particular dataset from the Thompson High School provided for the 9th graders' performance was flagged under suspicious of falsified math and reading test results. As such, an additional analysis was performed, with the exclusion of the 9th graders' results.

## School Performance Analysis Results
A number of discrepancies was found between the original dataset and the control, no ninth-graders, dataset.

<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/160524501-c268e303-9250-4d7f-bf92-5cf33adab5e2.png" />
  <img src="https://user-images.githubusercontent.com/99566803/160524505-e128dddb-bcc6-476e-a875-ac7258e44c7d.png" />
</p>

* As can be seen from the pictures, the exclusion of Thomas's High School small sample of ninth-graders' test results accounted for a slight decrease in the average reported math scores, overall percentage of students passing math and reading separately, as well as math and reading results combined.

* In terms of Thomas's High School grade distribution, the exclusion of ninth-graders' test results accounted for an almost 30% increase in overall percentage of students passing math and reading, both separately, and combined. However, no effect is found on the overall school district summary with or without the ninth-graders' test results.

* In terms of Thomas High School placement against the other district schools, there was also an almost 30% increase in the overall percentage of students passing the two courses examined.

<p align="center">
<img width="300" alt="mathbygradebeforecleaning" src="https://user-images.githubusercontent.com/99566803/160527987-6f4db02d-ed08-44b9-a9f1-baafe901a369.png">
<img src="https://user-images.githubusercontent.com/99566803/160528003-a56371f9-54f3-41a4-b5b8-cf4b801814db.png" /></p>
<p align="center">
<img width="300" alt="readingbygradebeforecleaning" src="https://user-images.githubusercontent.com/99566803/160528005-36435376-b0b5-43c6-833c-79af970ef44b.png">
<img src="https://user-images.githubusercontent.com/99566803/160528008-84a7606e-3270-4e57-bba4-dbe09f70d348.png" />
</p>

* Naturally, no conclusion can be made on the math and reading scores of the ninth-graders as all the scores were replaced with a "NaN" notation.

* No particular trends were found in regards to differences between the initial and the follow-up analysis when comparing the results by school spending, school size, or school type.

## Analysis Summary
The current analysis effectively demonstrates how one piece of information can influence the whole dataset. In terms of what was learned from the current dataset:

* 1. First, "erasing" suspicious data point with a "NaN" connotation can help identify outliers and overall inconsistencies in the data without majorly modifying the dataset itself.

* 2. Second, school spending, as well as the school size, and the school type, did not have an influence on the math and reading scores obtained by the students.

* 3. Third, Thomas High School ninth-graders were identified as outliers in the dataset, implying either an accidentally poor performance, or a thought-out score manipulation.

* 4. Finally, while the overall percentage of students who successfully passed the math and reading tests decreased across the whole district, Thomas High School, when adjusted for misplaced ninth-graders' results, retained its high performance position across the board, holding a second place across all 15 schools within the district.
