# Superstore Sales Analysis

## Overview
This project analyzes sales, profit, and shipping performance for a retail superstore dataset. The goal was to uncover business insights, identify profit-driving categories, and highlight areas of potential loss.

The project combines data analysis and business intelligence using SQL, Python, and Tableau to deliver both exploratory insights and interactive dashboards.

## Objectives

- Identify profitable product categories and sub-categories.
- Analyze sales and profit trends across regions and time periods.
- Explore the impact of shipping methods on profitability.
- Build an interactive Tableau dashboard for stakeholders.

## Table of Contents
1. [Data Overview](#data-overview)
2. [Key Findings](#key-analysis-and-insights)
3. [Technologies Used](#tools-and-technologies)
4. [Usage](#usage)
5. [Deliverables](#deliverables)
6. [Business Impact](#business-impact)
    
## Data Overview
The dataset contains 51,290 entries with 21 columns, including information on orders, customers, products, sales, profits, and shipping details.

## Key Analysis and Insights

1. Category & Subcategory Profitability
    - Technology products contributed the highest overall profit.
    - Furniture had the lowest profit margin, with some subcategories operating at a loss.

2. Regional Sales Trends
    - The West region outperformed other regions in both sales and profitability.
    - The South showed strong sales but thin profit margins.

3. Shipping Mode Analysis
    - Same-day shipping increased sales but reduced profit margins due to higher delivery costs.
    - Standard Class shipping was the most preferred shipping mode.

4. Time-based Trends
    - Seasonal spikes in November–December aligned with holiday sales.
    - Profitability dipped mid-year, suggesting opportunities for promotional campaigns.

## Tools and Technologies
- Python: Data cleaning & analysis (Pandas, Matplotlib, Seaborn)
- SQL: Querying and aggregating sales data
- Tableau: Dashboard creation & data visualization
- Jupyter Notebook: Documentation and reproducibility
   
## Usage
Open the `Superstore_Sales_Analysis.ipynb` file in Jupyter Notebook to view the full analysis.

## Deliverables
- **Exploratory Data Analysis (EDA):** Conducted in Python (visualizations, descriptive statistics).
- **SQL Queries:** Used to aggregate sales, profit, and regional performance.
- **Tableau Dashboard:** Interactive visual dashboard highlighting KPIs.

View the dashboards below:
- Sales Dashboard ![Dashboard 2.png](Dashboard%202.png)
- Profits Dashboard ![Dashboard 1.png](Dashboard%201.png)
  
Tableau Link: https://public.tableau.com/app/profile/kristian3758/viz/SuperstoreVisualizations_16619559626610/Dashboard2
              https://public.tableau.com/app/profile/kristian3758/viz/SuperstoreVisualizations_16619559626610/Dashboard1

## Business Impact
* If implemented in a real retail environment, these insights could help:
    - Focus marketing efforts on Technology and Office Supplies.
    - Re-evaluate pricing and discount strategies for Furniture.
    - Optimize logistics by promoting Standard Class shipping.
    - Plan seasonal campaigns during high-sales months to maximize profitability.
