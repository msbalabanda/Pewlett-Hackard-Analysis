# Pewlett-Hackard-Analysis

#PURPOSE OF THE PROJECT

The purpose of our project is to HELP Bobby determine the number of retiring employees by title and identify which employees are eligible to to participate in the mentorship program using SQL. We performed queries that retrieved the emp_no, first_name and last_name columns from the employees table and retrieved the title,from_date and to_date columns of the titles table from our data sets. Then we joined both these tables using the primary key,filtered the data by birth_date and put the information into a new table. In order to find the first occurance of the emp_no in the new table we created a unique_titles table using the Disctinct ON function and lasly to get the total number of each title from our unique_titles table we used the Order by count function. Our Results should help prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

#RESULTS

* The retirment_titles table shows us which employees are eligible for retirement and how long they have worked at each position over the course of their career.

* The unique titles table helps us identify the titles for employees of retirment age.

* Our retiring_titles shows show that majority of the employees of retirment age (57,668/90,398 = 64%) have senior titles.

* Lastly,in order to access  mentorship eligibility, we can see that most of these employees have senior titles.

#CONCLUSION

Based on our findings approximately 64% of the workforce is either retirment or mentorship eligible. As a result there will likely be many vacant positions over the next 5-10 years. The challenge will likely be finding qualified employees to fill these roles given the years of experience and seniority. In order to minimize this risk the company should invest in the mentorship program to ensure that upcoming employees will be able to successfully take over these jobs.



