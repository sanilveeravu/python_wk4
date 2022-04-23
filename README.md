# School District Analysis

## Overview of Analysis

The city school district requires to prepare all standardized test data for analysis, reporting and presentation. The outcome will be used to provide insights about performance trends and patterns for its schools. These insights will be taken into discussions and help in making strategic decisions regarding school budgets/priorities at the school/district levels by the school board and superintendent.

After the initial analysis, there was a report of academic dishonesty with evidence for the ninth grade in Thomas high school. With this in consideration an additional analysis was required with 7 key metrics excluding Thomas high school ninth grade for reading and math. As part of the analysis one additional requirement was to understand the impact of this exclusion to the metrics.

## Resources
- Data Source: students_complete.csv, schools_complete.csv
- Software: Python 3.9.7, Jupyter Notebook

---

## School District Performance Results

1. District Summary

When     |  District Summary Without Rounding
:-------------------------:|:-------------------------:
Before Correction   |  ![district_summary_df_not_rounded](Resources/district_summary_df_not_rounded.png)
After Correction   |  ![corrected_district_summary_df_not_rounded](Resources/corrected_district_summary_df_not_rounded.png)

When     |  District Summary Rounded
:-------------------------:|:-------------------------:
Before Correction   |  ![district_summary_df_rounded](Resources/district_summary_df_rounded.png)
After Correction   |  ![corrected_district_summary_df_rounded](Resources/corrected_district_summary_df_rounded.png)


2. School Summary

- Thomas High School Summary Before Correction 
![ths_summary_old_df](Resources/ths_summary_old_df.png)
- Thomas High School Summary After Correction Without Exclusion ![corrected_ths_summary_before_exclusion_df](Resources/corrected_ths_summary_before_exclusion_df.png)
- Thomas High School Summary After Correction With Exclusion ![corrected_ths_summary_after_exclusion_df](Resources/corrected_ths_summary_after_exclusion_df.png)

3. The top 5 / bottom 5 performing schools, based on the overall passing rate

- Top 5 Schools Before Correction
![top_schools](Resources/top_schools.png)
- Top 5 Schools After Correction
![corrected_top_schools](Resources/corrected_top_schools.png)

- Bottom 5 Schools Before Correction
![bottom_schools](Resources/bottom_schools.png)
- Bottom 5 Schools After Correction
![corrected_tbottom_schools](Resources/corrected_bottom_schools.png) 


4. The average math and reading score for each grade level from each school

Type |Before Correction     |  After Correction
:-------------------------:|:-------------------------:|:-------------------------:
Math Scores | ![math_scores_by_grade_not_rounded](Resources/math_scores_by_grade_not_rounded.png)    | ![corrected_math_scores_by_grade_not_rounded](Resources/corrected_math_scores_by_grade_not_rounded.png)
Reading Scores | ![reading_scores_by_grade_not_rounded](Resources/reading_scores_by_grade_not_rounded.png)    | ![corrected_reading_scores_by_grade_not_rounded](Resources/corrected_reading_scores_by_grade_not_rounded.png)


5. The scores by school spending per student

When     | Scores by School Spending Without Rounding
:-------------------------:|:-------------------------:
Before Correction   |  ![spending_summary_df_not_rounded](Resources/spending_summary_df_not_rounded.png)
After Correction   |  ![corrected_spending_summary_df_not_rounded](Resources/corrected_spending_summary_df_not_rounded.png)

When     |  Scores by School Spending Rounded
:-------------------------:|:-------------------------:
Before Correction   |  ![spending_summary_df_rounded](Resources/spending_summary_df_rounded.png)
After Correction   |  ![corrected_spending_summary_df_rounded](Resources/corrected_spending_summary_df_rounded.png)

6. The scores by school size 

When     | Scores by School Size Without Rounding
:-------------------------:|:-------------------------:
Before Correction   |  ![school_size_summary_not_rounded](Resources/school_size_summary_not_rounded.png)
After Correction   |  ![corrected_school_size_summary_formatted_not_rounded](Resources/corrected_school_size_summary_formatted_not_rounded.png)

When     |  Scores by School Size Rounded
:-------------------------:|:-------------------------:
Before Correction   |  ![school_size_summary_rounded](Resources/school_size_summary_rounded.png)
After Correction   |  ![corrected_school_size_summary_formatted_rounded](Resources/corrected_school_size_summary_formatted_rounded.png)

7. The scores by school type

When     | Scores by School Type Without Rounding
:-------------------------:|:-------------------------:
Before Correction   |  ![school_type_summary_not_rounded](Resources/school_type_summary_not_rounded.png)
After Correction   |  ![corrected_school_type_summary_not_rounded](Resources/corrected_school_type_summary_not_rounded.png)

When     |  Scores by School Type Rounded
:-------------------------:|:-------------------------:
Before Correction   |  ![school_type_summary_rounded](Resources/school_type_summary_rounded.png)
After Correction   |  ![corrected_school_type_summary_rounded](Resources/corrected_school_type_summary_rounded.png)

---

## School District Performance Summary

