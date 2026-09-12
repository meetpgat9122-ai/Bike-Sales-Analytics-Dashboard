# Bike Sales Customer Analytics

## 📌 Project Overview

This project analyzes customer data to understand bike purchasing behavior and identify customer segments that can be targeted through data-driven marketing strategies.

The analysis was performed using Microsoft Excel, with a focus on data cleaning, customer segmentation, Pivot Tables, Pivot Charts, and business insights.

## 🎯 Objectives

- Clean and validate customer data
- Segment customers based on age and income
- Analyze bike purchases across different demographic groups
- Identify high-performing customer segments
- Generate business insights for targeted marketing

## 🛠️ Tools & Technologies

- Microsoft Excel
- Excel Tables
- Data Cleaning
- Pivot Tables
- Pivot Charts
- Customer Segmentation
- Data Analysis

## 📊 Dataset

The dataset contains **1,000 customer records** with information including:

- Customer ID
- Gender
- Age
- Annual Income
- Children
- Marital Status
- Education
- Occupation
- Home Ownership
- Number of Cars
- Commute Distance
- Region
- Bike Purchase Status

## 🧹 Data Cleaning

The dataset was prepared and validated before analysis.

Key activities included:

- Checked for duplicate Customer IDs
- Checked for missing values
- Validated numerical and categorical fields
- Created `AgeGroup` categories:
  - 18–30
  - 31–40
  - 41–50
  - 51–60
  - 61+
- Created `IncomeGroup` categories:
  - Low
  - Medium
  - High

## 📈 Pivot Table Analysis

Multiple Pivot Tables were created to analyze purchasing behavior.

### 1. Gender Analysis

| Gender | Customers | Bike Buyers | Purchase Rate |
|---|---:|---:|---:|
| Female | 497 | 209 | 42.1% |
| Male | 503 | 220 | 43.7% |
| **Total** | **1,000** | **429** | **42.9%** |

### 2. Age Group Analysis

| Age Group | Customers | Bike Buyers | Purchase Rate |
|---|---:|---:|---:|
| 18–30 | 237 | 97 | 40.9% |
| 31–40 | 189 | 100 | **52.9%** |
| 41–50 | 207 | 85 | 41.1% |
| 51–60 | 196 | 86 | 43.9% |
| 61+ | 171 | 61 | 35.7% |

### 3. Age × Gender Analysis

The combined analysis identified:

- **Male + 31–40:** 56 buyers out of 99 customers → **56.6% purchase rate**
- **Male + 61+:** 30 buyers out of 89 customers → **33.7% purchase rate**

## 💡 Key Business Insights

1. The overall bike purchase rate was **42.9%**.
2. Customers aged **31–40** showed the highest observed purchase rate at **52.9%**.
3. The **Male + 31–40** segment showed the strongest observed purchase rate at **56.6%**.
4. Customers aged **61+** showed the lowest observed purchase rate at **35.7%**.
5. Customer segmentation can help businesses design more targeted marketing campaigns instead of using a single strategy for all customers.

## 💼 Business Recommendations

Based on the analysis:

- Prioritize testing targeted campaigns for the **31–40 age group**.
- Develop focused campaigns for the **Male + 31–40 segment**.
- Investigate the reasons behind lower purchase rates among older customers.
- Use demographic segmentation to personalize marketing strategies.
- Continue analyzing income and other customer attributes to identify additional opportunities.

## ⚠️ Analysis Limitation

This project is based on descriptive analysis using Excel Pivot Tables.

The identified relationships represent **observed patterns and purchase rates**. They do not establish that age or gender directly causes customers to purchase a bike.

## 📁 Project Files

- `BIKE_SALES_PROJECT.xlsx` — Excel dataset, analysis, Pivot Tables and charts

## 👨‍💻 Author

Priyanshu Kumar
