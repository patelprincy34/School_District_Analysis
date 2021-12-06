# School_District_Analysis
Module 4 project
# Overview of the school district analysis
## Purpose of the Project
#### The purpose of this project was to clean the data to exclude reading and math grades for Thomas High School ninth graders due to possible academic dishonesty (records appear to have been altered) and analyze data from school districts on student spending and standardized test scores to see trends and how well schools are performing. The school board will utilize the analysis and findings to make strategic decisions about the school budget and priorities.

## Resources
* Data Source: schools_complete.csv; students_complete.csv
* Source Code: PyCitySchools_Challenge_starter_code

## Results 
* How is the district summary affected?
  * There were no significant changes detected to any metrics under district summary
#### Original District Summary (before replacing 9th grade math and reading scores for Thomas High School with NaN values)
![image](https://user-images.githubusercontent.com/93439516/144770025-667de768-5cfb-4a67-b7c5-5a96afa617b8.png)
#### Updated District Summary (after replacing 9th grade math and reading scores for Thomas High School with NaN values)
![image](https://user-images.githubusercontent.com/93439516/144770219-c020d9b4-608f-4afe-a446-0519fbe174ff.png)

* How is the school summary affected?
  * For Thomas High School  
    * The average math score decreased slightly (from 83.42 to 83.35)
    * The passing math % decreased slightly (from 93.27 to 93.19)
    * The average reading score increased slightly (from 83.85 to 83.90) 
    * The passing reading % decreased slightly (from 97.27 to 97.02)
    * The overall passing % decreased slightly (from 90.95 to 90.63)
#### Original School Summary (before replacing 9th grade math and reading scores for Thomas High School with NaN values)
![image](https://user-images.githubusercontent.com/93439516/144770772-9845b898-8012-473e-a4cc-3d0568d6a3b3.png)


#### Updated District Summary (after replacing 9th grade math and reading scores for Thomas High School with NaN values)
![image](https://user-images.githubusercontent.com/93439516/144770686-7530979d-518a-40df-b5eb-5ab557b8ec7d.png)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * The overall school performance % decreases by less than 0.5% (from 90.95% to 90.63%) and does not have any affect on the   school's position in the top 5 high performing schools
  *  Thomas High School remains the 2nd top performing school

![image](https://user-images.githubusercontent.com/93439516/144770686-7530979d-518a-40df-b5eb-5ab557b8ec7d.png)

* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
    
    * Only grades for 9th grade for Thomas High School are affected and not available in updated dataset; Other math and reading scores are not affected for Thomas High School or any other school  
  
  * Scores by school spending
    
    * There were no changes detected to any metrics under $630-644 school spending category (Thomas High School falls in this category)
  
  * Scores by school size
    
    * There were no changes have been detected to any metrics under Medium(1000-2000) school size category (Thomas High School falls in this category)

  * Scores by school type
    
    * There were no changes have been detected to any metrics under Charter school category (Thomas High School falls in this category)

## School District Data Aanlysis Summary:

* The overall school performance % for Thomas High School decreased by less than 0.5% (from 90.95% to 90.63%)
* No scores are available for 9th grade for Thomas High School
* The passing math % for Thomas High School decreased slightly  (from 93.27 to 93.19)
* The passing reading % for Thomas High School decreased slightly (from 97.27 to 97.02)
