🏦 Bank Customer Churn Analysis

_A data-driven analysis project focused on identifying customer churn drivers and building actionable retention strategies for a retail banking environment using Power BI._

---

## 📌 Table of Contents
- [Overview](#overview)  
- [Business Problem](#business-problem)  
- [Dataset](#dataset)  
- [Tools & Technologies](#tools--technologies)  
- [Project Structure](#project-structure)  
- [Data Cleaning & Preparation](#data-cleaning--preparation)  
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
- [Research Questions & Key Findings](#research-questions--key-findings)  
- [Dashboard](#dashboard)  
- [Final Recommendations](#final-recommendations)

---

## Overview 
Customer churn is one of the most critical problems in the banking industry. Retaining existing customers is significantly cheaper than acquiring new ones, yet many banks are unable to identify early warning signals before a customer leaves.

This project analyzes customer demographics, activity behavior, financial attributes, and product usage patterns to uncover why customers churn and which customer segments are most at risk.
An interactive Power BI dashboard is built to make churn analysis intuitive and decision-ready for business stakeholders.

---

## Business Problem

The bank is experiencing consistent customer attrition, which leads to:
- Loss of revenue
- Reduction in deposits
- Higher customer acquisition costs
- Weakened customer lifetime value (LTV)

### The business needs to know:
- Why are customers leaving?
- Which customers are most likely to churn?
- What behaviors indicate churn risk?
- Which customers should be prioritized for retention?

Without deep churn insight, marketing campaigns remain generic and ineffective.

---

## Dataset

### Source
Internal HR dataset provided as:
- `Bank Customer Churn Prediction.csv` (raw data)
- `Cleaned_dataset.csv` (processed version for analysis)

### Size
- **10,000 customer records**

### Key Columns:

| Column          | Description                       |
| --------------- | --------------------------------- |
| CustomerId      | Unique customer identifier        |
| CreditScore     | Credit score of customer          |
| Geography       | Country (France, Germany, Spain)  |
| Gender          | Male / Female                     |
| Age             | Customer age                      |
| Tenure          | Years with bank                   |
| Balance         | Account balance                   |
| NumOfProducts   | Number of financial products      |
| HasCrCard       | Credit card ownership             |
| IsActiveMember  | Customer activity status          |
| EstimatedSalary | Annual income                     |
| Exited          | Churn flag (1 = Left, 0 = Stayed) |

















# 🏦📉Bank-Churn-Analysis

### 💡Project Overview

This Power BI project explores customer churn within the banking industry. By analyzing historical customer data, this project aims to identify key factors influencing churn and provide insights that could help banks improve customer retention and satisfaction. Through this analysis, we can better understand the behaviors and characteristics of customers who are likely to leave the bank, allowing the business to take proactive steps to reduce churn.

### 📊Features and Insights:
  
- Customer Segmentation: Analyze customers based on demographic data such as age, gender, and credit score groups. This helps identify specific customer segments that are more likely to churn.
- Churn Rate Calculation: Identify and visualize the churn rate across different customer segments.
- Visualizations: Interactive dashboards and charts to display churn rates, customer distribution, and factors affecting churn.

### 🗂️Data Source: 
- Dataset: The data used for this analysis is a synthetic dataset containing various attributes about bank customers, such as age, credit card status, active status, and more.

### 🛠️Tools Used:

- Power BI: For building interactive dashboards, data visualizations, and conducting data analysis.
- DAX (Data Analysis Expressions): Used for creating calculated columns and measures to perform more complex analyses in Power BI.
- Power Query: For transforming and cleaning data to ensure accurate analysis.

## 🖼️Power BI Dashboard

Below is a screenshot of the Power BI dashboard for Bank Churn Analysis:

<img width="918" height="518" alt="Churn_Analysis" src="https://github.com/komalb30/Bank-Churn-Analysis/blob/main/dashboard/Churn_Analysis.png" />

