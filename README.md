# Healthcare-Governance

=> About the Project

This project explores the Hospital Readmissions dataset from Kaggle to understand how well healthcare data is managed and how its quality can be measured.
I wanted to see what it means to apply data governance — things like completeness, accuracy, and consistency — to real-world data. Using Python, I built simple validation checks to spot data issues (missing values, outliers, redundant columns, etc.) and visualised the results in Power BI as an easy-to-read dashboard.
It’s a mix of technical analysis and governance principles — something between data science and data management.

=> Goal

1. To evaluate the quality of healthcare records using automated checks.
2. To design a dashboard that clearly shows where data issues exist.
3. To document simple governance rules that make data more reliable and transparent.

=> Dataset

Source: Kaggle – Hospital Readmissions
Size: 25,000 rows × 65 columns

The dataset includes information like:
1. Number of lab procedures, medications, and hospital stays
2. Patient demographics (encoded as booleans)
3. Readmission flags
4. Diagnosis categories

It’s one of those datasets that’s clean enough to explore, but messy enough to teach you what “data quality” really means.

=> What I Did
1. Explored the data in Python (using Pandas and Matplotlib).
2. Wrote small validation rules to detect:
  a. Missing or inconsistent data
  b. Negative or impossible values
  c. Columns with no variation
  d. Outliers in hospital stay durations
3. Exported the results as CSV files for visualisation in Power BI.
4. Designed a dashboard showing:
  a. How many records fail each rule
  b. Which fields are most incomplete
  c. Who “owns” each part of the data (in a governance context)

=> Tools I Used
1. Python (Pandas, Matplotlib) – for data checks and summaries
2. Power BI – for interactive visuals and KPIs
3. Markdown & Excel – for documenting data rules and ownership

=> Insights
1. About ~98% of records were valid, but a few fields had unexpected zeros or redundant values.
2. Some columns had no variation (e.g., always True/False), suggesting redundant encoding.
3. Power BI made it easy to communicate issues that would otherwise stay hidden in spreadsheets.
