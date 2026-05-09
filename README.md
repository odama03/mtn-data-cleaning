# MTN Nigeria — Data Cleaning Challenge

## Overview
This project tackles real-world data cleaning on a messy subscriber 
dataset from MTN Nigeria Communications Plc. The raw data contained 
duplicates, missing values, inconsistent casing, mixed date formats, 
negative values and outliers — all of which were identified and fixed.

## Tools Used
- Python
- Pandas
- Plotly
- Dash

## Dataset
200 rows of raw subscriber data including subscriber ID, date joined, 
full name, state, plan type, monthly recharge, data usage, call 
minutes, SMS count and status.

## Problems Fixed
- Duplicate subscriber IDs removed
- Mixed date formats standardized
- Inconsistent casing fixed (active/ACTIVE/Active)
- Bad state names corrected
- Negative SMS counts replaced
- Outlier values removed
- Missing values filled with median

## Dashboard Features
- KPI cards showing Total Subscribers, Duplicates Removed, Issues Fixed and Active Subscribers
- Data Issues Found bar chart
- Subscriber Status donut chart
- Subscribers by Plan Type bar chart
- Subscribers by State horizontal bar chart
- Avg Recharge by Plan bar chart
- Data Usage vs Call Minutes scatter chart

## Output
Cleaned dataset saved as MTN_Cleaned_Data.xlsx
