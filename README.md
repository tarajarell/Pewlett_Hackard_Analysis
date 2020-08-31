# Pewlett_Hackard_Analysis

## Purpose
### Overview
To prepare for upcoming staff retirements, Pewlett Hackard has tasked its Human Resources Department with compiling a list of soon-to be retirees at the company. Additionally, a list of staff who are 10 years from retirement age was compiled as candidates for a mentorship program. Mentorship candidates will work with soon-to-be retirees to better prepare those staff individually, and the company overall, for when the retirees leave. 

Four tables and CSV files were created to fulfill this brief and are described more in the Results and Summary sections below.

## Results
Overall, the data on the tables yielded information for all employee numbers of staff who were born between 1952 and 1955.
### Data
- 90,398 names with unique employee ID numbers were returned in the query for staff who may be eligible for retirement
- Senior Engineers had the highest count by employee title at 29,414 of the 90,398 employees found in the table
- 1,549 current employees (not retiring soon) are eligible under the birth date criteria to participate in the mentorship program
- 88,849 retiring employees would not have current non-retirement eligible employee mentor matches 

![Retirement_Count_by_Title.jpg](https://github.com/tarajarell/Pewlett_Hackard_Analysis/blob/master/Resources/Retirement_Count_by_Title.jpg)

## Summary
### Answers
-How many roles will need to be filled as the "silver tsunami" begins to make an impact?

90,398

-Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

Yes
### Recommendations
Additional queries could be run to create tables which include more specific information to help support Pewlett Hackard prepare for the upcoming "silver tsunami."
1. The data for retirees included past employees as well as current employees. The numbers of current employees who are eligible for retirement may be less than what we found in the abovementioned queries. It may benefit moving forward with the mentorship program to run a query and obtain how many retirement aged employees are currently working at Pewlett Hackard.
2. It may behoove the HR team to run another query related to the mentorship eligibility. Specifically, running the mentorship eligibility information to include more or less birth dates may enlarge or reduce the pool of employees to match with a soon-to-be retired emaployee.

![Retirees_List_syntax.jpg](https://github.com/tarajarell/Pewlett_Hackard_Analysis/blob/master/Resources/Retirees_List_syntax.jpg)
![Mentorship_Eligibility_syntax.jpg](https://github.com/tarajarell/Pewlett_Hackard_Analysis/blob/master/Resources/Mentorship_Eligibility_syntax.jpg)
