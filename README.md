# HCCB Sales Demand Forecasting

## Business Problem
Forecast brand-wise monthly demand for Hindustan Coca-Cola Beverages 
distributors for Sep-Dec 2018 to support inventory planning.

## Dataset
- 900K+ invoice line-item sales records
- 10 brands across multiple distributor-retailer outlets
- Period: Feb 2015 to Aug 2018
- Full dataset not included due to size (126MB)
- Sample of 10000 rows included as Salesdf_sample.csv

## Project Stages
1. Data Cleaning and Preprocessing
2. Brand × Month Aggregation
3. Exploratory Data Analysis
4. Exponential Smoothing Models (SES, Holt, HW-Additive, HW-Multiplicative)
5. Model Evaluation using MAE and MSE
6. Final Forecasts Sep-Dec 2018

## Key Findings
- Holt-Winters Multiplicative was best for 5 brands
- Portfolio-wide summer peak confirmed in April-May
- Thums Up showed the strongest seasonal pattern
- SES outperformed complex models for irregular brands

## Libraries Used
pandas | numpy | matplotlib | seaborn | statsmodels | sklearn

## Author
Shreshtha Sharma - [shreshthaphq39@gmail.com](mailto:shreshthaphq39@gmail.com)

PGDM in Data Science - Shanti Business School, Ahmedabad
