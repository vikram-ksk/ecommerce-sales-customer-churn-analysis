# E-Commerce Sales Performance & Customer Churn Analysis

## Project Overview

This project analyzes e-commerce sales performance, customer behavior, retention, customer segmentation, and churn risk using Python and Power BI.

The objective is to identify important business trends, understand customer value, analyze retention patterns, predict potential churn, and provide actionable business recommendations.

## Objectives

- Perform data cleaning and preparation
- Conduct Exploratory Data Analysis (EDA)
- Analyze sales trends by time, region, category, and product
- Perform Cohort Analysis and customer retention analysis
- Perform RFM Customer Segmentation
- Build a customer churn prediction model
- Create a Cohort Retention Heatmap
- Develop an interactive Power BI dashboard
- Provide business insights and recommendations

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab
- Power BI
- DAX
- Power Query
- Excel

## Project Workflow

### 1. Data Cleaning & Preparation
Checked the dataset for missing values, duplicate records, data types, date formats, negative values, and statistical outliers.

### 2. Exploratory Data Analysis
Analyzed sales performance across monthly and quarterly trends, regions, product categories, and top-selling products.

### 3. Cohort Analysis
Grouped customers based on their first purchase month and tracked customer retention across subsequent months.

### 4. RFM Customer Segmentation
Calculated:
- Recency
- Frequency
- Monetary Value

Customers were segmented into:
- Champions
- Loyal Customers
- At Risk
- Potential Loyalists
- New Customers
- Lost

### 5. Churn Prediction
Used a historical cutoff of October 1, 2017 and defined churn based on no purchase during the following 90-day period.

A Decision Tree Classifier was used with customer behavioral features including Recency, Frequency, Monetary Value, Average Order Value, and Total Quantity.

### 6. Power BI Dashboard
Created an interactive dashboard containing:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Average Sales
- Monthly Sales Trend
- Quarterly Sales Trend
- Sales by Region
- Sales by Category
- Top 10 Products
- RFM Segment Revenue
- Customer Churn Overview
- Cohort Retention Analysis

Interactive filters were provided for Region, Category, and Order Date.

## Key Insights

- Total Sales: 2.30M
- Total Profit: 286.40K
- Total Orders: 5.009K
- Total Customers: 793
- Technology was the highest-sales category.
- West was the highest-performing region.
- Canon imageCLASS 2200 Advanced Copier was the top-selling product.
- Loyal Customers generated the highest RFM segment revenue.
- At Risk customers represent an important customer-retention opportunity.
- Customer retention generally decreases after the first purchase.

## Churn Model Results

- Churned Customers: 357 (45.19%)
- Non-Churned Customers: 433 (54.81%)
- Model: Decision Tree Classifier
- Accuracy: 55.06%
- Precision: 50.00%
- Recall: 23.94%
- F1 Score: 32.38%

The churn model is treated as an initial baseline and can be improved with additional customer behavior features, more historical data, and model comparison.

## Business Recommendations

- Target At Risk customers with personalized offers and re-engagement campaigns.
- Retain Loyal and Champion customers through loyalty programs and personalized recommendations.
- Run targeted win-back campaigns for Lost customers.
- Monitor cohort retention to identify customer engagement decline.
- Monitor sales, customer, RFM, and churn KPIs through the Power BI dashboard.

## Project Deliverables

- Jupyter/Google Colab Notebook
- Cleaned Dataset
- RFM Segmentation Dataset
- Cohort Retention Dataset
- Customer Churn Dataset
- Power BI Dashboard
- Executive Summary Report
