# WIDL Supermarket: Avocado Sales & Demand Analysis

## 🥑 Project Overview
This project was completed as part of a technical assessment for a Data Analyst role at WIDL, a large international supermarket chain. The objective was to perform an exploratory data analysis on a dataset of weekly avocado sales across US stores. The goal of this project is to uncover historical consumption patterns, regional demand trends, and price elasticity to help WIDL optimize their inventory and pricing strategies.

*(overall dashboard image here: `![Avocado Dashboard Overview](https://github.com/helin-c/avocado-sales-analysis/blob/main/Dashboard.png?raw=true)`)*

## 🎯 The Challenge
The WIDL data team requested an Excel-based analysis to answer four key business questions:
1. Are there any macro trends over time relating to avocados across all regions?
2. Which regions had the highest demand for avocados in 2018?
3. Is there a difference in demand for conventional vs organic avocados?
4. If the price of avocados is higher, how does this impact demand?

## 🛠️ Tools & Techniques
* **Microsoft Excel:** Used for data cleaning, aggregation, and analysis.
* **Pivot Tables & Slicers:** Created dynamic, interactive data summaries allowing users to filter by Region, Type, and Year.
* **Data Visualization:** Built clear, professional Line charts, Bar charts, and Scatter plots to visually communicate trends.
* **Statistical Analysis:** Calculated correlation coefficients and R-squared values to mathematically measure price vs. volume relationships.

## 📊 Key Insights

### 1. Macro Trends over Time
Total avocado sales volume increased steadily from 4.4 Billion in 2015 to nearly 5 Billion in 2017, indicating growing consumer demand and market popularity. The sharp decline observed in 2018 is attributed to incomplete, partial-year data in the provided dataset rather than an actual drop in product popularity.
*(Insert Q1 screenshot here: `![Macro Trends](https://github.com/helin-c/avocado-sales-analysis/blob/main/Q1.png?raw=true)`)*

### 2. Regional Demand (2018)
Excluding the national "Total US" aggregate, the West and California regions recorded the highest demand in 2018, followed by the South Central region. This indicates that avocado consumption is heavily concentrated in highly populated areas with localized access to agricultural supplies.
*(Insert Q2 screenshot here: `![Regional Demand](https://github.com/helin-c/avocado-sales-analysis/blob/main/Q2.png?raw=true)`)*

### 3. Conventional vs. Organic Preference
There is a massive, distinct gap in demand between avocado types. Conventional avocados absolutely dominate the market with 15.1 Billion units sold over the recorded period, compared to just 0.4 Billion units for organic avocados. This highlights that WIDL consumers heavily prefer the more affordable and widely available conventional options.
*(Insert Q3 screenshot here: `![Conventional vs Organic](https://github.com/helin-c/avocado-sales-analysis/blob/main/Q3.png?raw=true)`)*

### 4. Price Elasticity & Impact on Demand
The scatter plot analysis reveals a weak negative correlation (-0.19) between average price and total volume sold. While demand generally decreases as prices rise, the low R-squared value (0.037) indicates that price alone explains only a very small fraction of the variation in demand. Factors such as regional preferences, seasonality, and promotional events likely play a much more significant role in driving WIDL's sales volume.
*(Insert Q4 screenshot here: `![Price vs Demand](https://github.com/helin-c/avocado-sales-analysis/blob/main/Q4.png?raw=true)`)*

## 📂 How to Use This Repository
* Download the `.xlsx` file to interact with the raw data, pivot tables, and dynamic slicers.
* Navigate to the **Dashboard** tab within the workbook for a high-level summary and interactive visual reporting.
