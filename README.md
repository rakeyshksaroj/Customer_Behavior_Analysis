Customer Shopping Behavior Analysis
📌 Overview

This project performs an end-to-end analysis of customer shopping behavior based on 3,900+ retail transactions.
It combines Python (EDA), SQL (business insights), and Power BI (visual analytics) to uncover patterns in spending, customer segmentation, product performance, and subscription behavior.

The goal is to demonstrate strong skills in data cleaning, feature engineering, SQL analysis, dashboarding, and business problem-solving—key competencies for a Data Analyst role.

📊 Project Objectives

Clean and preprocess raw retail data

Perform exploratory data analysis using Python

Build SQL queries to extract actionable business insights

Develop interactive dashboards using Power BI

Provide data-driven business recommendations

📁 Dataset Summary

Total Records: 3,900
Columns: 18

Key Features:

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Attributes: Category, Item Purchased, Amount, Size, Color, Season

Behavioral Metrics: Discount Applied, Promo Code, Previous Purchases, Frequency of Purchases

Ratings & Experience: Review Rating, Shipping Type

Missing Values:

37 missing entries in review_rating handled using median imputation by category.

🧹 Data Cleaning & Preparation (Python)

Performed using Pandas, NumPy, Matplotlib, Seaborn.

✔ Loaded and inspected dataset
✔ Standardized column names to snake_case
✔ Handled missing values (category-wise median imputation)
✔ Removed redundant fields like promo_code_used
✔ Feature engineering:

age_group via binning

purchase_frequency_days
✔ Data validation checks
✔ Loaded cleaned dataset into PostgreSQL database

🧮 Exploratory Data Analysis (Python)

Key findings:

Distribution of age groups and spending

Correlation between discount usage and purchase amount

High-value product categories

Rating distribution across categories

Seasonal buying trends

Visualized using bar charts, box plots, and heatmaps.

🗄 SQL Analysis (MySQL)

SQL queries focused on extracting business-oriented insights:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Review Rating

Shipping Type Spend Comparison

Subscribers vs Non-Subscribers (Revenue + Avg Spend)

Products Most Dependent on Discounts

Customer Segmentation (New / Returning / Loyal)

Top 3 Products per Category

Repeat Buyers & Subscription Likelihood

Revenue Contribution by Age Group

These queries demonstrate clear command over window functions, aggregation, joins, and case classifications.

📊 Power BI Dashboard

Created a fully interactive dashboard with:

Revenue trends

Customer segments

High-value age groups

Discount influence on sales

Product & category performance

Shipping type comparison

Subscription behavior analysis

The dashboard communicates insights clearly for decision-making teams.

💼 Business Recommendations

Based on insights:

Increase Subscription Conversions: Highlight exclusive subscriber perks

Strengthen Customer Loyalty Programs: Reward repeat buyers

Optimize Discount Strategy: Improve margins while maintaining engagement

Promote Top-Rated Products: Leverage high customer satisfaction

Age-Group Targeted Marketing: Focus on high-revenue demographics

Enhance Express Shipping Offers: High-value customers prefer faster delivery

🛠 Tools & Technologies

Python: Pandas, NumPy, Matplotlib

Databases: PostgreSQL

SQL Skills: Aggregations, Window Functions, CTEs, Joins

Power BI: Interactive dashboards

GitHub: Version control and project documentation

📂 Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/                  # Raw and cleaned datasets
├── notebooks/             # Python EDA notebooks
├── sql_scripts/           # SQL analysis files
├── powerbi/               # Dashboard PBIX file
├── images/                # Visual outputs
└── README.md              # Project documentation

🔍 Key Skills Demonstrated

Data Cleaning & Preprocessing

Exploratory Data Analysis

SQL for Business Insights

Dashboard Development

Feature Engineering

Insight Communication

End-to-end Data Analytics Workflow
