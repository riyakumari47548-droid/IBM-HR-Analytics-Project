### Employee Attrition & Workforce Analysis ###

### IBM SkillsBuild Data Analytics with AI Project

## Project Overview

This project analyzes employee attrition patterns using the IBM HR Analytics dataset. The analysis focuses on understanding how employee attrition varies across different employee and workplace factors.

The project uses Python for data analysis and visualization to identify patterns in employee attrition and present findings that can support workforce-related decision making.

## Project Objective

The objective of this project is to analyze employee attrition patterns and identify how attrition varies across different employee and workplace factors such as department, overtime, job role, job satisfaction, monthly income, and total work experience.

The analysis uses exploratory data analysis and data visualization to identify patterns in the dataset.

## Dataset

The dataset contains information about 1,470 employees across 35 columns.

It includes employee demographics, department and job role information, job satisfaction, overtime, income, work experience, and other workplace-related attributes.

The target variable for this analysis is `Attrition`, which indicates whether an employee left the company (`Yes`) or stayed (`No`).

### Dataset Source

The dataset was obtained from Kaggle:

**HR Analytics Dataset:**  
https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- Jupyter Notebook

## Analysis Performed

The project includes the following analysis steps:

- Data loading and initial inspection
- Data cleaning and preparation
- Missing value checking
- Duplicate record checking
- Constant column identification
- Exploratory Data Analysis (EDA)
- Attrition analysis by department
- Attrition analysis by overtime
- Attrition analysis by job role
- Attrition analysis by job satisfaction
- Attrition analysis by monthly income
- Attrition analysis by total working years
- Attrition analysis by business travel
- Data visualization
- Key findings and conclusion

## Key Findings

- The overall employee attrition rate was **16.12%**.
- Employees who worked overtime had an attrition rate of **30.53%**, compared with **10.44%** for employees who did not work overtime.
- The **Sales** department had the highest attrition rate among the three departments at **20.63%**.
- **Sales Representatives** had the highest attrition rate among the analyzed job roles at **39.76%**.
- The **Low income** group had an attrition rate of **29.27%**.
- Employees with **0–5 years** of total work experience had an attrition rate of **28.80%**.

These findings describe patterns observed in the dataset and do not establish that any individual factor directly causes employee attrition.

## Project Structure

IBM_HR_Analytics_Project
│
├── data
│   └── HR Analytics.csv
│
├── notebooks
│   └── Riya_HR_Analytics.ipynb
│
├── README.md
├── requirements.txt
└── Riya_ProjectReport.docx
## How to Run the Project

Download or clone the project repository.

Install the required Python libraries using:
pip install -r requirements.txt

Open Riya_HR_Analytics.ipynb using Jupyter Notebook, JupyterLab, or Google Colab.

If using Google Colab, upload the HR Analytics.csv dataset when prompted by the notebook.

Run the notebook cells from beginning to end to reproduce the analysis and visualizations.

## Conclusion

This project provides a descriptive analysis of employee attrition patterns across different employee and workplace factors.

The analysis shows that attrition rates varied across departments, overtime groups, job roles, income groups, experience groups, job satisfaction levels, and business travel categories.

The project demonstrates the use of Python, Pandas, and Matplotlib for data cleaning, exploratory data analysis, and visualization.