# School District Analysis

## Overview

The school board believes that the reading and math grades for Thomas High School might have been altered. By analyzing the results with and without those grades we aim to determine whether they are consistent with the remaining school district. 

## Results

For this analysis we will use the term "full" to represent the original source data and "adjusted" to represent the data with results for Thomas High School grade 9 students removed.

### District Summary
Comparing the full district summary with the adjusted data, although the average math and reading scores are generally unchanged, the passing percentages are higher when the THS 9th grade results are included. Overall passing rates are 1 percentage point higher.

* Math passing percentage decreases from 75.9% to 74.8% when THS 9th grade scores are excluded.
* Reading passing percentage decreases from 86.8% to 85.7% when THS 9th grade scores are excluded.
* Overall passing percentage decreases from 65.9% to 64.9% when THS 9th grade scores are excluded. Given the population size this means approx. 392 more students would be passing if the percentages with THS 9th grade included are accurate.

Full district summary:
![Full district summary](<./Resources/full/district.png>)

Adjusted district summary:
![Adjusted district summary](<./Resources/adjusted/district.png>)

### School Summary

As expected, only the Thomas High School statistics have changed between the full and adjusted output. By examining the school summary we can observe the following:

* Average math scores are higher at 83.42 in the full data set vs. 83.35 in the adjusted data set, increasing the passing rate by approximately 0.1 percentage point (93.27% vs. 93.19%).
* Average reading scores are lower at 83.85 in the full data set vs. 83.90 in the adjusted data set, whereas the passing rate increased by approximately 0.3 percentage points (97.31% vs. 97.02%).

The lower average reading scores suggest that any intentional changes to the scores would benefit the students (and the school's ranking) only in math.

Full school summary:
![Full school summary](<./Resources/full/school-summary.png>)

Adjusted school summary:
![Adjusted school summary](<./Resources/adjusted/school-summary.png>)

### Thomas High School's Relative Performance

Thomas High School is among the top five schools in the district by overall passing percentage. The relative rank is unchanged by excluding Grade 9 results; in both cases Thomas High School comes in second for overall passing percentage.

Full top 5:
![Full top 5 schools](<./Resources/full/top-schools.png>)

Adjusted top 5:
![Adjusted top 5 schools](<./Resources/adjusted/top-schools.png>)

### Math and Reading Scores by Grade

### Scores by School Spending

### Scores by School Size

### Scores by School Type

## Summary

