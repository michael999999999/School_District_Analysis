# School_District_Analysis

## Project Overview
A local school board is requesting an analysis of school data within it's district. Upon review of the data, concerns were raised regarding academic dishonesty with regard to 9th graders from Thomas High School, and a subsequent re-analysis of the data was performed.

## Resources
- Data Source: schools_complete.csv, students_complete.csv, clean_students_complete.csv, missing_grades.csv
- Software: Python 3.9.7, conda 4.12.0, jupyter notebook 6.4.8, pandas 1.41

## Summary
The re-analysis of the school data shows that:
 - Thomas High School's overall passing percentage dropped from 90.94% to 90.63%.
 - Thomas High School's math passing percentage dropped from 93.27% to 93.18%.
 - Thomas High School's reading passing percentage dropped from 97.30% to 97.01%.
 - Thomas High School's average math score decreased from 83.41 to 83.35.
 - Thomas High School's average reading score actually increased from 83.84 to 83.89.
 - Thomas High School maintained #2 in the top five highest ranked schools.
 - No other metrics were affected.

## Challenge Summary
Analysis prior to nullifying 9th Grade Thomas High School scores:
![Analysis prior to nullifying 9th Grade Thomas High School scores:]https://github.com/michael999999999/School_District_Analysis/blob/main/Resources/PCS_top_schools.png

Analysis after nullifying 9th Grade Thomas High School scores:
![Analysis after nullifying 9th Grade Thomas High School scores:]https://github.com/michael999999999/School_District_Analysis/blob/main/Resources/PCS_Challenge_top_schools.png

As evidenced by the above photos, upon invalidating the 9th grade scores from Thomas High school several passing percentages and average scores were lowered from the original analysis: overall passing percentage, math passing percentage, reading passing percentage, and average math score. Interestingly, average reading scores actually increased.

In the grand scheme of this analysis, the lowered scores and percentages show that the 9th graders at Thomas High School perhaps had a hand in raising overall results from Thomas High School. Additionally, the higher average reading score demonstrates that the 9th graders at Thomas were bringing down the rest of the school.

However, erasing scores completely does not give an accurate picture into the success rate at Thomas High School. This only serves to lower the school as a whole, as shown above. To add to that, this unfairly penalizes students that may have had no hand in any academic impropriety. I would suggest administering a retest, then using those results within this analysis to help better gauge how Thomas High School helps to prepare the future leaders of this world.
