# Pewlett-Hackard-Analysis

## Overview of Analysis

The purpose of this analysis is to help company executives visualize the number of potential retirees within our departments to better understand what they describe as the "silver tsunami". This analysis helps prepare management in advance of this change by preparing transitional programs, like a mentorship program to facilitate the training program for the influx of new workers. 

Large CSV datasets were provided by management as a resource. The programming language used in this analysis was SQL which was enabled in the platform PgAdmin with PostgreSQL as the database engine. An entity relationship diagram was also developed within the QuickDBD app to help develop a plan for the analysis. 

## Results

### Entity Relationship Diagram (source: QuickDBD)

<img src="https://github.com/katmarcin/Pewlett-Hackard-Analysis/blob/553594a6045e12569536480265404c15e52db69f/EmployeeDB.png" width="350" height="400"/>

### Analysis of Employees Planning to Retire by Title

https://github.com/katmarcin/Pewlett-Hackard-Analysis/blob/553594a6045e12569536480265404c15e52db69f/Data/retiring_titles.csv

* Approximately 70% of staff that plan to retire are either senior engineers or senior staff
* In total, 72,458 employees should be planning to retire soon per our assumptions
* 1,090 assistant engineers plan to return soon, approximately 1.5% of all staff
* Only 2 managers should be planning to retire soon

### Analysis of Employees Eligible for Mentorship Program

<img src="https://github.com/katmarcin/Pewlett-Hackard-Analysis/blob/421913614f0f8747d434e18fe0153e48f345f043/retiring_titles.png" width="200" height="250"/>

https://github.com/katmarcin/Pewlett-Hackard-Analysis/blob/553594a6045e12569536480265404c15e52db69f/Data/membership_eligibility.csv"

* 1,940 employees are eligible for the mentorship program

## Summary

72,458 roles within 7 different titles will need to be filled as the "silver tsunami" begins to make an impact. This value is derived from the second table under "Results". 

https://github.com/katmarcin/Pewlett-Hackard-Analysis/blob/f71b813cb1a406e16b2152e22623c3f93fee68da/expanded_membership_eligibility.csv

There are not enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. Less than 3% of employees are eligible for the mentorship program, yet 72,458 roles will need to be filled in the near future. Pewlett Hackard needs to expand the eligibility criteria for the mentorship program to prevent disaster when the tsunami hits. By expanding the criteria years from 1960 to 1970, we can capture groups of individuals who are early retirees, late retirees, as well as standard-age retirees. In our original analysis we had only limited the data to those born in 1965. This query would be a very beneficial addition to the analysis. The above link is attached to the raw data of employees who are eligible to mentor when the year of birth range is expanded. This data was added and extracted from our our analysis in pgAdmin. A whopping 117,139 employees are able to mentor, which is more than enough to mentor. In fact, not everyone will have the opportunity to mentor and in this case it would have to be a first come, first choose volunteer basis, rather than a required program for transitioning into retirement. 





