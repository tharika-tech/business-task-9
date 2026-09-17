# Business Sales Performance Dashboard — Tableau

## Project Overview

This project analyzes business sales performance over time using Tableau Public. A business sales dataset from Kaggle was used to create an interactive dashboard containing a line graph and three additional visualizations.

The dashboard helps identify sales trends, high- and low-performing periods, category performance, regional profitability, and the relationship between sales and profit.

## Objectives

- Analyze changes in sales over time.
- Identify the highest and lowest sales periods.
- Identify increasing and decreasing sales trends.
- Detect sudden peaks and drops in sales.
- Compare sales performance across product categories.
- Analyze profit across different regions.
- Examine the relationship between sales and profit.
- Provide business insights and recommendations.

## Dataset

**Dataset:** Superstore Sales Dataset  
**Source:** Kaggle

### Important Fields Used

| Field | Purpose |
|---|---|
| Order Date | Time-based analysis |
| Sales | Main business measure |
| Profit | Profitability analysis |
| Category | Category comparison |
| Region | Regional analysis |

## Visualizations

### 1. Monthly Sales Trend — Line Graph

Shows how total sales changed month by month.

**Fields Used:**
- Columns → `MONTH(Order Date)`
- Rows → `SUM(Sales)`

This visualization is used to identify the highest sales period, lowest sales period, increasing trends, decreasing trends, and sudden peaks or drops.

### 2. Sales by Category — Bar Chart

Compares total sales across different product categories.

**Fields Used:**
- Columns → `Category`
- Rows → `SUM(Sales)`

The visualization compares Technology, Furniture, and Office Supplies.

### 3. Profit by Region — Bar Chart

Compares total profit across different geographical regions.

**Fields Used:**
- Columns → `Region`
- Rows → `SUM(Profit)`

This helps identify regions generating higher and lower profit.

### 4. Sales vs Profit — Scatter Plot

Examines the relationship between sales and profit for different categories.

**Fields Used:**
- Columns → `SUM(Sales)`
- Rows → `SUM(Profit)`
- Detail → `Category`

Different categories are represented using different colors.

## Interactive Filter

A **Region** filter was added to the dashboard.

Users can select individual regions or view all regions. The filter allows users to interactively explore the dashboard based on region.

## Dashboard

All four visualizations were combined into a single Tableau Public dashboard.

**Dashboard Title:** Business Sales Performance Dashboard

### Dashboard Components

1. Monthly Sales Trend
2. Sales by Category
3. Profit by Region
4. Sales vs Profit
5. Interactive Region Filter

## Business Insights

1. **Technology** records the highest total sales among the three categories, followed by Furniture and Office Supplies.

2. **West** has the highest total profit at approximately **$108,418**, followed by East at approximately **$91,523**.

3. **South** generates approximately **$46,749** in profit, while Central records approximately **$39,706**, showing differences in regional profitability.

4. The monthly sales line graph shows noticeable fluctuations throughout the year, including significant increases around September and November.

5. The scatter plot demonstrates that higher sales do not automatically result in the same level of profit, highlighting the importance of considering profitability alongside sales volume.

## Business Recommendations

### 1. Focus on High-Performing Categories

The business can analyze the strong sales performance of **Technology** and ensure adequate inventory and marketing support for products within this category.

### 2. Improve Lower-Profit Regions

The business should investigate the factors contributing to lower profitability in regions such as **Central and South**, including pricing, discounts, product mix, and operating costs.

## Tools Used

- Tableau Public — Data visualization and dashboard creation
- Kaggle — Dataset source

## Author

**Naren M**

## Tableau Public Dashboard

**Dashboard Link:**  
[Add your Tableau Public dashboard URL here after publishing.](https://public.tableau.com/views/task-9_17896286637730/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
