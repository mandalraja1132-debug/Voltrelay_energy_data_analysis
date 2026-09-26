# VoltRelay Energy – Data Analytics Hackathon ⚡

This project is my submission for the **Data Analytics Hackathon v2 conducted by Gradient**.

I analyzed VoltRelay Energy's battery-swapping data to understand how the network is performing, where service issues are happening, how battery health affects range, and what factors are related to rider retention.

## About the Project

The dataset covers **January 2024 to June 2025** and contains around:

- 3.9M swap events
- 20K riders
- 6.5K batteries
- 152 stations
- 44K support tickets

## What I Analyzed

I focused on six main areas:

- Network growth and revenue
- Swap failures and service issues
- Station and city-level performance
- Battery health and observed range
- Pricing and fleet partner performance
- 30-day rider retention

## Key Findings

- Monthly swap attempts increased from **108K to 332K**.
- Monthly revenue increased from **₹6.2M to ₹19.7M**.
- Completion rate decreased from **95.6% to 91.4%**.
- **58.2% of unsuccessful attempts** were related to no charged battery being available.
- Batteries with **95–100% SOH** averaged around **72.8 km**, compared with **44.4 km** for batteries below 80% SOH.
- Major support complaints included **no battery available, low range, and long queues**.
- Monthly 30-day rider retention was generally above **98%** in the analyzed cohorts.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel

## Project Workflow

```text
Data Cleaning
     ↓
Data Validation
     ↓
Exploratory Data Analysis
     ↓
KPI Analysis
     ↓
Segmentation & Comparison
     ↓
Business Insights
     ↓
Recommendations
