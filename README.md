# Customer Shopping Behavior Analysis

## Project Overview
This project performs an end-to-end analysis of customer shopping behavior using a dataset of 3,900 retail transactions. The goal of this analysis is to uncover actionable insights into customer purchasing habits, segment the customer base, and identify key drivers of revenue and engagement.

The analysis workflow spans data cleaning and exploratory data analysis in Python, advanced querying in PostgreSQL, and interactive data visualization in Power BI.

## Repository Contents
- **`Business Problem Document.pdf`**: Details the business context, objectives, and questions this analysis aims to answer.
- **`customer_shopping_behavior.csv`**: The dataset containing 3,900 retail transactions with 18 features including customer demographics, purchase details, and behavioral metrics.
- **`Customer_Shopping_Behavior_Analysis.ipynb`**: A Jupyter Notebook detailing the data loading, cleaning, feature engineering, and initial exploratory data analysis using Pandas, Matplotlib, and Seaborn.
- **`customer_shopping_behavior_analysis.sql`**: A collection of PostgreSQL queries used to answer specific business questions, perform customer segmentation, and calculate KPIs (like revenue by season, discount impact, and customer loyalty).
- **`customer_behavior_dashboard.pbix`**: An interactive Power BI dashboard providing a visual representation of the key findings, allowing stakeholders to explore trends by season, category, and customer segment.

## Tools & Technologies Used
- **Python**: Pandas, Matplotlib, Seaborn (Data Cleaning & EDA)
- **SQL (PostgreSQL)**: Advanced querying, aggregations, window functions, and CTEs
- **Power BI**: Interactive Data Visualization & Dashboarding
- **Jupyter Notebook**: Interactive coding environment

## Key Findings & Business Insights
- **Customer Segmentation**: Customers were successfully segmented into 'New', 'Returning', and 'Loyal' tiers based on historical purchase data (percentile-based thresholds).
- **Subscription Impact**: Analysis revealed that subscribers do not necessarily spend more on average per transaction compared to non-subscribers, suggesting that subscription status alone is not the sole indicator of customer value.
- **Discount & Promo Effectiveness**: Top discounted products and their correlation with higher-than-average spending were identified.
- **Seasonal Trends**: Evaluated revenue and order volume by season to optimize inventory and marketing campaigns.

## How to Use
1. **Python Analysis**: Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook or Google Colab to review the data cleaning and initial EDA steps.
2. **SQL Queries**: The `customer_shopping_behavior_analysis.sql` file contains ready-to-run queries. You can import the cleaned CSV into a PostgreSQL database and execute these queries to replicate the insights.
3. **Dashboard**: Open `customer_behavior_dashboard.pbix` using Power BI Desktop to interact with the visualizations.
