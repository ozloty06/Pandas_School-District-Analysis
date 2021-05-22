# School_District_Analysis
In partnership with Maria, Chief Data Scientist for PyCity School District, the following report is prepared by special request from the school board.

## Overview of School District Analysis
This analysis investigates a potential incident(s) of academy dishonest related to standardized testing scores at Thomas High School in the PyCity School District. Our analysis includes a review of standardized testing scores for math and reading, reviewing student and school performance while comparing the results to other schools in the district. The output of this analysis will help the school board make strategic decisions on issues such as school funding and understanding needs for further confidential investigations. Due to Family Educational Rights and Privacy Act(FERPA)of 1974, individual student results will not be included in our reporting.

Python, Pandas library, and Jupyter Notebook were used to conduct this analysis.

## Results

#### District Results
At the district level, a summary of of total schools and total students was provided along with a total budget for the district. Overall district performance was also summarized with average math and reading scores and percentage of students passing** math, reading or both. With 461 Thomas High School 9th graders out of a total of 39,170 students in the whole district representing only 1.2% of the student population, it's not surprising to see the average scores and passing percentages remain unchanged (see Figure 1).

##### Figure 1. District Summary 
![Image of original district summary](https://github.com/ozloty06/School_District_Analysis/blob/main/Resources/District_Summary_original.png)

#### School Results
When we assessed the district's 15 schools individually, we saw some variance in both average scores and passing percentages for Thomas High School when we removed the 9th grade students' scores from our data set. For reference, there are 461 students in 9th grade at Thomas High School out of a total 1635 students in 9th-12th grade, or 28% of the student body at Thomas High School is in 9th grade.

Interestingly, average math scores increased by 0.07% when we included 9th grade scores, while average reading scores decreased by 0.05% when looking at all students of Thomas High School. When we look at passing percentages, we find that 0.09% more students passed math when 9th grade scores are included while 0.29% more students passed reading when 9th grade scores are included. Further, the overall passing rate climbs from 90.63% to 90.95%, a difference of 0.32%, when 9th grade scores are included in Thomas High School's results (see Figure 2 and Figure 3).

##### Figure 2. Subset of School Summary of All Grades (9th-12th) at Thomas High School.
![Image of original school summary](https://github.com/ozloty06/School_District_Analysis/blob/main/Resources/School_Summary_original.png)

##### Figure 3. Subset of School Summary Adjusted to Include Only 10th-12th Grades at Thomas High School.
![Image of adjusted school summary](https://github.com/ozloty06/School_District_Analysis/blob/main/Resources/School_Summary_adjusted.png)

Looking at math and reading performance averages for other charter schools on Figures 2 and 3, we see an average math score of 83.4 and an average reading score of 83.8, which is in line with what we see at Thomas High School in both tables, regardless of inclusion/exclusion of 9th grade students. The average percent passing math at the other charter schools is 93.69% and the average percent passing reading is 96.34%. Thomas High School's percentage of students passing math and reading came in at 93.19%-93.27% and 97.02%-97.31% respectively with 9th graders included in the higher percentage for both. Removing the 9th grade scores would drop Thomas High School's passing percentages across both subjects, taking math further from the average of these 3 other charter schools for math while closer to the average performance for reading. 

** Passing scores are scares equal to 70 or greater.
#### Additional Results

When we review the scores by grade, 9th graders at Thomas High School, like their fellow 10th-12th graders, perform on average similarly to other school districts. Reviewing scores by spending, once again we are comparing results with only a 1.2% difference in student population over the entire district so it's not surprisng to see no difference in average scores by spending. (Note: Thomas High School is in a $630-644 spend per student range).

As a medium sized school, similar to our findings in school spending, results are not impacted regardless of the inclusion of Thomas High School 9th graders in our data set. Lastly, this is consistent for school type, where Thomas High School results do not vary across data sets.

## Summary
In summary, the district results are not impacted by the removal of Thomas High School 9th grade student scores from our data set. It is likely this is the result of these 9th graders representing only 1.2% of the student population.

Observed changes between the data sets includes:
- a slight increase of 0.07% in average passing math scores when 9th grade students from Thomas High School are included in our analysis.
- a slight increase in 0.09% of students passing math when 9th grade students from Thomas High School are included in our analysis.
- an increase of 0.29% of students passing reading when 9th grade students from Thomas High School are included in our analysis.
- an increase of 0.32% of overall passing (passing both math and reading)hen 9th grade students from Thomas High School are included in our analysis.

It is recommended that the school board further investigate potential academic dishonesty if sufficient evidence exists beyond our analysis, which does not indicate a strong liklihood of tampering. If an investigation does take place, the school board would be best served beginning their investigation reviewing reading scores that may have been adjusted to meet the standards for passing (a score of 70 or greater).
