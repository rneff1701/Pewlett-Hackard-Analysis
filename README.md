# Pewlett-Hackard-Analysis
## Project Overview
### Analysis to determine which current employees are approaching retirement age based on a date of birth between 1952 and 1955.  This is to help Pewlett Hackard to plan for this wave of retirees and ensure there is no disruption to their work force.

Upon receiving the raw data files an ERD was created to map the primary keys between all the tables.
![EmployeeDB](https://user-images.githubusercontent.com/95188079/152237909-0581a167-b29c-4238-91ca-45afb62dc5b2.png)

- Using the Employees, Department Employee, and Titles tables analysis was done to identify the retiring employees by title.
- Duplicates were identified in this file and an updated table was created by looking for distinct values in the employee number and filtering the to_date to keep only current employees.
- This data was summed up at the title level and it was identified that the job titles "Senior Engineer" and "Senior Staff" had the highest number of upcoming retirees.
- Lastly, a table of current employees that were born in 1965 and are eligible for a mentorship program was created.

How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
