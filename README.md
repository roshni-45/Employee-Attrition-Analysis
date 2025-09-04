# Employee-Attrition-Analysis
This is a complete, real-world data analyst portfolio project based on an Employee Attrition dataset of 1,470 employees. The project simulates a real analyst workflow, from raw data exploration to actionable business insights.
Project Purpose

The goal is to understand factors affecting employee turnover and provide insights for HR management to improve retention. The analysis covers:

Attrition trends across departments, job roles, and gender

Salary and performance analysis to identify pay gaps

Impact of overtime, work-life balance, and promotions on attrition

Employee satisfaction and career growth insights

This project is ideal for:

📊 Data Analyst aspirants building a portfolio

📚 Anyone learning SQL and database analysis hands-on

💼 Preparing for HR analytics, People Analytics, or general data analyst roles


Dataset Overview

Rows: 1,470 employees

Columns: 30 attributes including Age, Department, JobRole, MonthlyIncome, Attrition, JobSatisfaction, WorkLifeBalance, OverTime, PerformanceRating, and more.

Source: HR dataset imported into PostgreSQL


Key Columns: 

- EmployeeNumber – Unique employee ID

- Attrition – Yes/No (indicates if employee left)

- Department – Employee department

- JobRole – Employee role

- MonthlyIncome – Employee salary

- JobSatisfaction & WorkLifeBalance – Satisfaction metrics (1–4 scale)

- OverTime – Yes/No flag

- PerformanceRating – 1–4 scale

- YearsAtCompany, YearsSinceLastPromotion – Experience metrics


Project Workflow:

-Database & Table Creation
Created the EmployeeAttrition table in PostgreSQL with appropriate data types.

-Data Import
Imported dataset into PostgreSQL using pgAdmin or the \copy command.

-Data Exploration & Cleaning
Checked for null values and cleaned data
Explored attrition patterns across departments, roles, and demographics

-SQL Analysis Queries
Employee attrition trends
Salary insights and performance evaluation
Job level vs attrition
Overtime, work-life balance, promotions, and experience analysis



Key Insights

Sales and R&D departments show the highest attrition

Lower-level employees and those working overtime are more likely to leave

High performers generally receive higher hikes, but some are underpaid

Longer gaps since last promotion correlate with higher attrition

Higher work-life balance improves job satisfaction
