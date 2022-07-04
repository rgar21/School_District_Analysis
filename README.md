# School_District_Analysis

Analyzing school district test scores using Pandas in Jupyter Workbook

## Overview of Project:

The purpose of this project is to compile test score results for school district administrator review 

### Purpose

The intent of this analysis to provide a clean and concise overview of test score results while filtering out potential academic dishonesty. Our client will be able to use this analysis to find the relationship between test scores and several factors such as school type, school size, and budget per student.

## Results

After filtering out the requested data for THS (Thomas High School) we see that the district results are largely the same. Here is a snapshot of our initial analysis:

![Initial_school_summary](https://user-images.githubusercontent.com/106921601/177205077-d59c59cd-fcb7-4318-a01f-ee5f779c8496.PNG)

When we review the below revised school summary we see that there is less than a third of a percentage point drop between the overall passing percentage for THS.

![Revised_school_summary](https://user-images.githubusercontent.com/106921601/177205093-12678470-446d-4552-8bc1-f3dd3ba784df.PNG)

In the above images we can see that by removing 9th grade THS students from this analysis yielded very little change to our overall school and district summaries. THS is still a top 5 school in the district after the changes were made.

## Summary

The most plausible outcome that we can draw from comparing these two summaries is that by removing the 9th grade students from THS we mostly affect these 4 key metrics: 
  * The total number of students
  * The total number of students at THS
  * The average math and reading scores at THS
  * The overall passing percentage at THS

Overall, THS is still the number two performing school at this school district, and the removal of the THS 9th grader scores had little to no effect on the overall district summary. However, due to strict adherence to laws from the state this revised summary was still important to maintaining academic honesty. 

