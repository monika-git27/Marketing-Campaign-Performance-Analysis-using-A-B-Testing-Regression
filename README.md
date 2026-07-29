# Marketing-Campaign-Performance-Analysis-using-A-B-Testing-Regression


## Overview

Marketing teams invest heavily in digital advertising, but determining which platform delivers better results requires data-driven analysis. This project analyzes the performance of **Facebook Ads** and **Google Ads** campaigns over a one-year period using **statistical analysis, Exploratory Data Analysis (EDA), and predictive modeling**.

The project evaluates campaign effectiveness through key performance metrics, validates differences using **A/B Testing**, and builds a **Linear Regression model** to predict conversions from user engagement.

---

## Business Problem

Digital marketers often face questions such as:

- Which advertising platform generates more conversions?
- Are the observed performance differences statistically significant?
- How strongly do ad clicks influence conversions?
- Can future conversions be predicted from campaign activity?

This project answers these questions using statistical techniques and data-driven analytics to support marketing decision-making.

---

## Dataset

The dataset contains **365 daily advertising records** from Facebook and Google advertising campaigns.

### Features

- Date
- Ad Views
- Ad Clicks
- Conversions
- Cost
- Click-Through Rate (CTR)
- Cost Per Click (CPC)
- Additional campaign performance metrics

---

## Project Workflow

### 1. Data Preparation

- Imported and explored campaign data using **Pandas**
- Performed data quality checks
- Cleaned and prepared data for analysis
- Generated analytical features

### 2. Exploratory Data Analysis (EDA)

Performed detailed analysis including:

- Daily conversion trends
- Monthly campaign performance
- Weekday vs. Weekend analysis
- Click and conversion distributions
- Correlation analysis
- Facebook vs. Google performance comparison

### 3. Statistical Analysis

Performed an **Independent Two-Sample A/B Test (t-test)** to determine whether Facebook and Google campaigns differ significantly in average conversions.

### 4. Predictive Modeling

Built a **Linear Regression** model to estimate Facebook conversions based on ad clicks.

### 5. Business Insights

Generated actionable recommendations to support:

- Marketing budget allocation
- Campaign optimization
- Performance forecasting
- Data-driven decision making

---

## Key Findings

- Facebook Ads achieved an average of **11.74 daily conversions**, compared to **5.98** for Google Ads.
- Statistical testing confirmed that the difference in average conversions was **statistically significant**.
- A **strong positive correlation (r = 0.87)** exists between ad clicks and conversions.
- The Linear Regression model achieved an **R² score of 76.35%**, indicating strong predictive capability.
- Seasonal and weekday analyses revealed noticeable fluctuations in campaign performance.

---

## Technologies Used

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

### Statistical Techniques

- A/B Testing
- Independent Two-Sample t-Test
- Correlation Analysis
- Linear Regression

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning & Transformation
- Statistical Hypothesis Testing
- Marketing Analytics
- Predictive Analytics
- Data Visualization
- Business Insight Generation
- Regression Modeling

---

## Results

| Metric | Result |
|---------|--------|
| Dataset Size | 365 Daily Records |
| Facebook Mean Conversions | 11.74 |
| Google Mean Conversions | 5.98 |
| Correlation (Clicks vs. Conversions) | 0.87 |
| Regression Model R² | 76.35% |

---

## Business Recommendations

- Allocate a larger share of the marketing budget toward the higher-performing advertising platform identified through analysis.
- Use click-based forecasting to estimate future campaign conversions.
- Continuously validate campaign performance using A/B testing before making budget allocation decisions.
- Monitor seasonal and weekly trends to optimize campaign scheduling and maximize conversions.

---

## Conclusion

This project demonstrates how statistical analysis and predictive modeling can transform raw marketing data into actionable business insights. By combining **EDA, hypothesis testing, and machine learning**, the analysis provides an evidence-based approach for evaluating campaign effectiveness and supporting strategic marketing decisions.
