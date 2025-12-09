Employee-Attrition-Analysis-using-Excel
🚀 Project Overview

This project focuses on analyzing employee attrition within an organization using Microsoft Excel. The goal of the study is to understand why employees are leaving, identify high-risk groups, and provide data-driven recommendations to improve retention.

I performed complete data cleaning, transformation, exploratory analysis, and visualization to uncover the factors that significantly influence employee turnover.

📂 Dataset

The dataset contains information on 2925 employees, including:

Employee demographics (Age, Gender, Marital Status)

Job details (Department, Job Role, Tenure)

Compensation (Salary, Salary Hike %, Income Band)

Performance Ratings

Job Satisfaction & Environment Satisfaction

Overtime Status

Attrition Status (Yes/No)

After cleaning:

Total Employees: 2925

Employees Who Left: 473

Attrition Rate: 16.17%

🔧 Data Cleaning Steps

To prepare the dataset for analysis, I performed:

Removed duplicate entries using Employee Number

Filled missing categorical values with “Unknown”

Filled missing numeric fields (e.g., Age, Income, Tenure) with median values

Standardized inconsistent labels (e.g., department names)

Ensured all attrition-related columns were aligned

Added calculated fields:

Age Band

Income Band

Tenure Group

Current vs Ex-Employee flag

These steps ensured accuracy in all pivot tables and visualizations.

📊 Analysis Conducted

The analysis covered the following major areas:

Attrition by Department & Job Role
Sales and Technical roles showed the highest attrition

HR and senior roles had the lowest attrition

Demographic Factors
Attrition counts (out of 472 measured cases):

Age 25–34 → 223

Under 25 → 75

Age 35–44 → 100

Age 45–54 → 50

Over 55 → 22

Male attrition → 299

Female attrition → 173

Single employees → 236 (highest)

Tenure
Major exits occur in the first 1–3 years

1 year → 118

2 years → 54

3 years → 42

Attrition stabilizes after 5+ years.

Compensation Insights
Income band attrition:

High → 110

Medium → 248

Low → 114

Salary hike comparison:

Stayed → 15.23%

Left → 15.13% 👉 Hike % is not reducing attrition.

Work Satisfaction & Overtime
Job Satisfaction (Attrition Count):

Rating 1 → 132

Rating 2 → 91

Rating 3 → 144

Rating 4 → 105

Environment Satisfaction:

Rating 1 → 144 (highest attrition risk)

Overtime:

With Overtime → 252

No Overtime → 220

🔍 Key Insights

From the analysis, the highest-risk groups are:

Employees aged 25–34

Employees in low/medium salary bands

Employees with low job or environment satisfaction

Overtime workers

Employees in Sales and Technical roles

Early-tenure employees (0–2 years)

Single employees

These groups repeatedly appeared across multiple dimensions of the analysis.

🎯 Recommendations

To reduce attrition, the following steps are strongly recommended:

Strengthen onboarding and first-year support

Minimize excessive overtime or compensate it fairly

Improve job satisfaction and environment satisfaction

Review compensation strategies for lower bands

Provide growth and development pathways for the 25–34 age group

Offer targeted support to Sales and Technical teams

Conduct periodic employee engagement check-ins

📈 Tools & Techniques Used

Microsoft Excel

Pivot tables

Pivot charts

Conditional formatting

Data cleaning functions

Slicers for interactivity

Data visualization (Bar charts, Pie charts, Line graphs, Heatmaps)

📁 Project Structure 📦 Employee-Attrition-Analysis ├── Data Cleaning.xlsx ├── Final Dashboard.xlsx ├── Department & Role Analysis.xlsx ├── Demographic Analysis.xlsx ├── Compensation Analysis.xlsx ├── Work Satisfaction Analysis.xlsx ├── README.md ← (you are here) └── Presentation Script.pdf

(You can adjust filenames to match your actual uploads.)

🧑‍💼 About the Project

This project demonstrates end-to-end HR analytics capability including:

Data cleaning

Business framing

Exploratory data analysis

Visualization

Insight storytelling

Recommendations

All insights have been derived from real company datasets and validated through pivot-table analysis.

⭐ How to Use This Repository

Download the Excel files

Explore pivot tables and slicers

Review the readme for understanding the process

Use the dashboard for presentations

Refer to the script for oral presentation
