Healthcare Risk Classification Using Data Analysis
Overview

This project focuses on analyzing patient health data to classify individuals based on their health risk levels using data analysis techniques. The workflow follows a structured approach to ensure accurate insights and meaningful visualization of health patterns.

The main steps include:

Data generation and preprocessing
Data cleaning and validation
Exploratory Data Analysis (EDA)
Risk classification using rule-based logic
Data visualization and group analysis

The goal is to identify patients with potential health risks (Low, Medium, High) and help in early detection and preventive healthcare.

Dataset Source

Synthetic healthcare dataset generated using Python

Features Include
Age
Gender
Blood Pressure
Sugar Level
Cholesterol
Heart Rate
Target Variable
Risk Level (Low / Medium / High)
Objectives
Analyze patient health patterns
Identify key factors affecting health risks
Classify patients into risk categories
Detect high-risk individuals early
Visualize relationships between health attributes
Project Highlights
1. Data Generation & Preprocessing
Generated a synthetic dataset using NumPy
Structured data using Pandas
Handled and checked for missing values
Ensured clean and consistent data format
2. Data Cleaning
Inspected dataset using .info() and .describe()
Verified missing values
Removed null entries if present
Prepared dataset for analysis
3. Risk Classification Logic
Applied rule-based classification using thresholds:
High Risk: High blood pressure, sugar level, or cholesterol
Medium Risk: Moderately elevated values
Low Risk: Normal health metrics
Created a new feature Risk_Level based on conditions
4. Exploratory Data Analysis (EDA)
Analyzed distributions of age and health parameters
Studied relationships between features
Identified patterns affecting health risk
Grouped data based on gender and age
5. Data Visualization
Histogram: Age distribution
Bar chart: Risk level distribution
Pie chart: Percentage of risk categories
Scatter plot: Age vs Blood Pressure
Box plot: Cholesterol outliers
Heatmap: Correlation between features
6. Group Analysis
Compared risk levels across genders
Analyzed average blood pressure across different ages
Identified trends in health indicators
Tools and Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
<img width="786" height="597" alt="image" src="https://github.com/user-attachments/assets/108c3721-a5e3-4cc2-986b-66aa2aee1ac4" />
<img width="802" height="649" alt="image" src="https://github.com/user-attachments/assets/f55fe1aa-a1b3-4b76-a544-0f8c6fc4149b" />
<img width="784" height="579" alt="image" src="https://github.com/user-attachments/assets/98626da2-ae47-4a83-a55d-93459b794e95" />
<img width="711" height="592" alt="image" src="https://github.com/user-attachments/assets/cc8b0fc4-163e-4f08-87b2-0109aa563baf" />
