# HR Analytics: Employee Attrition & Retention Strategy

## Project Overview
This project is an in-depth data analysis of the **IBM HR Analytics dataset** to identify the key factors that lead to employee attrition. The primary goal is to translate historical data into actionable insights and provide strategic recommendations to the HR and management teams to improve employee retention.

This analysis covers the full workflow of a Data Analyst, from data cleaning and exploratory data analysis (EDA) to presenting conclusions and business recommendations.

## Background & Business Context
In today's competitive talent market, retaining skilled employees is no longer just an HR goal—it's a critical business strategy. Employee attrition, or turnover, is more than just a vacant desk. It carries significant direct and indirect costs, from recruitment expenses to lost productivity. Industry studies estimate that replacing an employee can cost between **1.5 to 2 times their annual salary.**

This project addresses this challenge by taking a data-driven approach. Instead of relying on guesswork, this analysis uses historical employee data to uncover the hidden patterns and root causes of attrition. The ultimate goal is to empower the company to move from a reactive approach to a proactive, predictive strategy for talent retention.

## Problem Statement

The company senses a challenge in retaining its employees, but the scale, causes, and most affected groups have not yet been clearly quantified. This analysis aims to provide clarity by answering three interconnected core business questions.

1. **What is the scale of the attrition problem?**<br>
The first and most fundamental step is to objectively understand the scope of the problem.
    * What is the overall employee attrition proportion or rate across the company?

1. **What are the key drivers behind attrition?** <br>
Once the scale of the problem is known, the next objective is to identify the root causes of why employees leave.
    * **Workload**: To what extent does working overtime increase an employee's likelihood of leaving?
    * **Job Role**: Which specific job roles exhibit the highest attrition rates?
    * **Compensation**: How significant is the difference in monthly income between employees who leave and those who stay?

2. **What is the common profile or characteristics of employees who resign most frequently?** <br>
To ensure effective solutions, it's crucial to know which groups are most at risk.
    * **Job Satisfaction**: Is there a direct correlation between an employee's reported job satisfaction level and their decision to leave?
    * **Demographics**: Are there any demographic patterns (like marital status) that clearly define a high-risk group?
    * **Tenure**: At what stage of their career is an employee most likely to leave? 

## Dataset
The analysis uses the public [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) dataset from Kaggle. It contains 1,470 rows of fictional employee data with 35 features covering demographics, job roles, and satisfaction ratings.

## Tools & Libraries
* Language: `Python`
* Libraries:
    * `Pandas`: For data manipulation and cleaning.
    * `Matplotlib` & `Seaborn`: For data visualization.
* Environment: Jupyter Notebook

## Project Workflow
* **Data Loading & Understanding:** Load the dataset and perform an initial inspection of its structure, data types, and quality.
* **Data Cleaning:** Handle duplicate data, missing values (if any), and remove irrelevant columns.
* **Exploratory Data Analysis (EDA):** Visualize the data to answer the questions in the problem statement and uncover hidden insights.
* **Conclusion & Recommendations:** Summarize all key findings and translate them into strategic, actionable business recommendations.

## Key Findings
* **The overall attrition rate is 16.1%.**
* The primary drivers of attrition are **excessive workload (overtime) and low compensation.**
* The highest-attrition roles are **Sales Representative and Laboratory Technician.**
* The most vulnerable segments are **new hires (within their first 1-2 years)** and employees with **low job satisfaction.**

## Business Recommendations
* Perform a salary benchmark analysis against industry standards and a workload audit to reduce reliance on overtime.
* Develop a structured, year-long onboarding program to support new hires and show a clear career path.
* Use regular "surveys" to detect dissatisfaction early and take preventive action.