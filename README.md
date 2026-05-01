# FUTURE_DS_02

# 📊 Customer Retention & Churn Analysis

# 📌 Project Overview

This project focuses on analyzing customer retention and churn behavior using a telecom subscription dataset to uncover key insights that drive customer attrition and engagement. The primary objective is to identify churn patterns, high-risk customer segments, and factors influencing customer retention, while providing actionable recommendations to improve business performance.

The workflow combines Python (Jupyter Notebook) for data cleaning and transformation and Microsoft Power BI for building an interactive dashboard that supports business storytelling and decision-making.

# 🎯 Objectives

The primary objective of this project is to conduct a comprehensive analysis of customer retention and churn behavior in a subscription-based business environment. Specifically, the project aims to:

* Develop a clear understanding of customer churn patterns and trends
* Identify high-risk customer segments that are more likely to discontinue services
* Analyze customer lifetime behavior, including tenure distribution and engagement levels
* Examine the impact of key variables such as contract type, services subscribed, and payment methods on churn
* Uncover key drivers influencing customer attrition
* Provide data-driven and actionable recommendations to improve customer retention and reduce churn
  
# 📊 Dataset
* **Dataset Used:** Telco Customer Churn Dataset
* **Source:** Kaggle

The dataset consists of approximately **7,000+** customer records (rows) and **21** features (columns), representing various aspects of customer behavior and subscription details.

# 🔍 Dataset Features Include:
## Customer Demographics:
Gender, Senior Citizen status, Partner, Dependents

## Account & Subscription Information:
Tenure, Contract type, Internet service, Phone service, Multiple lines

## Services Used:
Online security, Online backup, Device protection, Tech support, Streaming TV, Streaming movies

## Billing & Payment Details:
Monthly charges, Total charges, Payment method, Paperless billing

## Target Variable:
Churn status (Yes/No), indicating whether a customer has discontinued the service

# 🛠️ Tools and Technologies

## 1. Python (Jupyter Notebook)
* pandas – data cleaning and manipulation
* numpy – numerical operations
* Feature engineering for churn analysis

## 2. Microsoft Power BI
* Interactive dashboard creation
* KPI tracking and visualization
* Customer segmentation analysis
* Business storytelling

# 🔄 Data Processing (Python)

The dataset was cleaned and prepared through a structured pipeline:

* Handled missing values and inconsistencies
* Removed duplicate records
* Converted categorical and numerical data types
* Standardized variables for analysis
* Created new features:
* Tenure Groups (0–12, 12–24, etc.)
* Total Services Used
* Churn indicators
* Ensured data quality for accurate reporting

The cleaned dataset was exported and used in Power BI for visualization.

# 📊 Dashboard (Power BI)

The Power BI dashboard provides a comprehensive view of customer behavior and churn drivers across two main pages.

# 🔑 Key Metrics
* Total Customers: 7K
* Retained Customers: 5K
* Churned Customers: 2K
* Churn Rate: 26.54%
* Average Monthly Charges: 64.76
* Average Tenure: 32.37 months
  
# 📈 Visualization
* Churn Rate by Tenure Group (Clustered Column Chart)
* Churn Rate by Total Services Used (Clustered Column Chart)
* Churn by Contract Type (Clustered Bar Chart)
* Churn by Payment Method (Clustered Bar Chart)
* Churn by Senior Citizen Status (Clustered Bar Chart)
* Monthly Revenue Loss due to Churn (Clustered Column Chart)


# 📊 Dashboard Link

### [Click here to view the Customer Retention and Churn Analysis Dashboard](https://shorturl.at/wDzHR) 

# Key Insights

## 1. Early Customer Churn is Highest

Customers within the first 12 months exhibit the highest churn rate (47.68%), which steadily declines as tenure increases.

**Insight:** The initial customer lifecycle stage is the most critical period for retention, indicating onboarding and early engagement gaps.

## 2. Contract Type Strongly Influences Retention

Month-to-month customers have a significantly higher churn rate (42.71%) compared to one-year and two-year contract customers.

**Insight:** Long-term contracts act as a strong retention mechanism and reduce customer attrition.

## 3. Customer Engagement Reduces Churn

Customers using fewer services are more likely to churn, while those subscribed to multiple services show significantly lower churn rates.
The anomaly at 2 services (36.42% churn) is driven by Fiber + Phone customers without technical support.

**Insight:** Higher product engagement increases customer stickiness and lifetime value.

## 4. Payment Method Impacts Churn Behavior

Customers using electronic checks show the highest churn (45.29%), while automatic payment methods have lower churn rates.

**Insight:** Friction in payment processes may contribute to customer drop-off.

## 5. High-Value Churn Segment Identified

Month-to-month customers contribute the most to Monthly Recurring Revenue (MRR) loss, with over 121K revenue lost from this group.

**Insight:** This segment represents the highest-risk and highest-impact churn group.

# Recommendation
## 1. Improve Early Customer Experience

Focus on onboarding strategies within the first 90 days:

* Personalized onboarding journeys
* Customer education and support
* Early engagement campaigns

## 2. Promote Long-Term Contracts

Encourage customers to switch to longer-term plans by:

* Offering discounts or incentives
* Providing loyalty rewards
* Highlighting long-term value benefits
  
## 3. Increase Product Engagement

Drive adoption of additional services by:

* Bundling services
* Offering personalized recommendations
* Cross-selling relevant features
  
## 4. Optimize Payment Systems

Reduce churn related to payment friction by:

* Encouraging automatic payment methods
* Providing flexible billing options
* Offering incentives for switching payment types
  
## 5. Target High-Risk Segments

Develop retention strategies for:

* Month-to-month customers
* Senior citizens
* Low-engagement users

Use targeted campaigns, offers, and proactive support.

# 📂 Project Structure
```
FUTURE_DS_02/
│
│  
├── dashboard/
│   ├── dashboard1.png
│   └── dashboard2.png
│
├── data/
│   ├── telco_customer_churn.csv
│   └── telco_cleaned.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
└── README.md
```
# 🚀 Skills Demonstrated

• Data cleaning & preprocessing
• Exploratory data analysis (EDA)
• Customer segmentation
• Churn & retention analysis
• Feature engineering
• Business KPI analysis
• Data visualization (Power BI)
• Insight generation & storytelling

# 🤝 Acknowledgement

I would like to sincerely thank Future Interns for providing this valuable real-world internship opportunity.

This experience allowed me to work on a practical business problem, apply customer analytics techniques, and generate actionable insights that reflect real industry scenarios. Through this project, I strengthened my skills in data analysis, retention strategy, and dashboard storytelling using Python and Power BI.

I am grateful for the opportunity to further develop my capabilities as a Data Science & Analytics student.
