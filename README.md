# Human Resources Data Cleaning and Analysis with Python and Power Bi For visualisation part.

## Table of contents
- [Project Overview](#project-overview)
- [Data description](#data-description)
- [Tools](#tools)
- [Data Cleaning](#Data-cleaning)
- [Data Analysis (Questions)](#data-analysis)
- [Dashboard analysis with Powerbi](#dashboard-analysis-with-powerbi)
- [Summary](#summary)
- [Ref](#ref)

### Project Overview

<p align="center">
<img src="https://github.com/smdhen/Human-Resources-Data-Cleaning-and-Analysis-with-Python-and-Power-Bi-For-visualisation-part/assets/96498289/973c54bb-8647-41c7-88da-c43eaea1e17b" width="500"/> 
</p>

This project is dedicated to analyzing human resource data for a company. The initial phase focuses on data cleaning using Python.

Once the data is clean , the next phase involves  analysis using Pandas.

Furthermore, the project incorporates the visualization aspect using [Power Bi](https://learn.microsoft.com/fr-fr/power-bi/). 

### Data description
![Screenshot from 2024-04-09 00-18-25](https://github.com/smdhen/Human-Resources-Data-Cleaning-and-Analysis-with-Python-and-Power-Bi-For-visualisation-part/assets/96498289/dfa23e01-3269-47f5-b065-a2fbb9b32a67)

termdat :  The termination date in the dataset signifies various employment outcomes, including termination by the employer, voluntary resignation by the employee, or dismissal. When the termination date is represented as NaT (Not a Time), it indicates that the employee is currently still employed and has not yet undergone any termination process.

### Tools

1. Python : Data Cleaning 
2. Data Cleaning : [Pandas](https://pandas.pydata.org/docs/user_guide/10min.html#grouping)
3. Power-bi : Creating Reports

### Data Cleaning

This involves handling missing values, removing duplicates,removing inutil data,Formatting date ...

### Data Analysis

The Analysis will be done Using Pandas By answering variouse questions. Various statistical techniques and methodologies are applied to uncover patterns, trends.

#### Questions Are 

    1- What is the gender breakdown of employees in the company?
    2- What is the race/ethnicity breakdown of employees in the company?
    3- What is the age distribution of employees in the company?
    4- How many employees work at headquarters versus remote locations?
    5- What is the average length of employment for employees who have been terminated?
    6- How does the gender distribution vary across departments and job titles?
    7- What is the distribution of job titles across the company?
    8- Which department has the highest turnover rate?
    9- What is the distribution of employees across locations by state?
    10- How has the company's employee count changed over time based on hire and term dates?
    11- What is the tenure distribution for each department?
    12- What is the gender breakdown of employees who have quit the company?
    13- What is the gender breakdown of employees who still work in the company?
    14- What is the gender breakdown of employees who have been hired by the company?
    15- How does the hiring of employees compare to the employees who have quit over the years, categorized by gender?
    16- What is the average age of employees hired by the company, categorized by gender?
    17- What is the average age of employees who have quit the company, categorized by gender?

These questions encompass various aspects of employee demographics, turnover rates, hiring trends, and tenure distribution, providing a comprehensive understanding of the workforce dynamics within the company.

### Dashboard analysis with Powerbi

![Capture_0](https://github.com/smdhen/Human-Resources-Data-Cleaning-and-Analysis-with-Python-and-Power-Bi-For-visualisation-part/assets/96498289/4a6fd52d-9156-4748-a4f7-88b9172a6035)

![Capture_1](https://github.com/smdhen/Human-Resources-Data-Cleaning-and-Analysis-with-Python-and-Power-Bi-For-visualisation-part/assets/96498289/75e6d373-fec6-4209-a3b9-2b57432676f5)

![Capture_3](https://github.com/smdhen/Human-Resources-Data-Cleaning-and-Analysis-with-Python-and-Power-Bi-For-visualisation-part/assets/96498289/b7487efa-88d6-4998-b334-cba1093f9ae4)

### Summary

Conclusions from the HR data analysis:

1. The gender distribution among employees is approximately balanced, although males are slightly more predominant.
2. A significant majority, over 70%, of employees work at headquarters.
3. Ohio stands out as the state with the highest number of employees.
4. The average length of employment is approximately 7 years, indicating that employees typically stay with the company for this duration before leaving.
5. There is a noticeable upward trend in the net change percentage of employees over the years.
6. The average age of employees is 39 years old, with the oldest being 58 and the youngest being 21.
7. More than 75% of employees are aged 48 years or older.
8. Males are both hired and terminated (or departed) more frequently than females.
9. From 2000 to 2020, the number of hired employees ranged between 380 and 478 for both genders.
10. The number of terminated or departed employees has seen a decrease over the years.
11. The auditing department experiences the highest frequency of terminations, indicating potential areas for improvement in employee retention strategies. Conversely, the sales department boasts the longest average tenure among employees, highlighting the department's stability and possibly effective management practices.

This analysis provides valuable insights into workforce demographics, employee performance, terminated rates.tenur and more.
### Ref
[Youtube](https://www.youtube.com/watch?v=PzyZI9uLXvY&t=1040s) Link to Vidio where this project has been done but Usin SQL and Power Bi by Irene-arch 

<!---
Github](https://github.com/Irene-arch/HR-Dashboard-MySQL-PowerBI) Repository by  Irene-arch
-->

