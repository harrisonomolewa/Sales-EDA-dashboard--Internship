# Sales Performance Analysis — Data Analyst Internship (Task 1)

Exploratory data analysis and interactive dashboard built on a retail sales dataset covering Office Supplies, Electronics, and Furniture transactions from March 2020 to March 2025.

## Project Overview

This project was completed as Task 1 of a Data Analyst internship, focused on:
- Cleaning and preparing a raw sales dataset
- Performing exploratory data analysis (EDA)
- Answering structured business questions
- Building an interactive dashboard

## Repository Structure


## Tools Used

- **Power BI** — data cleaning (Power Query) and the primary interactive dashboard
- **HTML/JavaScript (Chart.js)** — a supplementary web-based interactive dashboard, for easy sharing/viewing without Power BI Desktop
- **Word** — final EDA report

## Dataset

1,194 transaction records with the following fields: Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode, Order Date, Customer Name, State, City, and Year-Month.

Source dataset: [Sales Dataset on Kaggle](https://www.kaggle.com/datasets/shantanugarg274/sales-dataset)

## Data Cleaning

Cleaning was performed in Power Query within Power BI, including:
- Checking for missing values, duplicates, and invalid entries
- Standardising date fields and verifying consistency against the Year-Month column
- Reviewing category, payment mode, and location fields for consistent formatting

Full cleaning notes are documented in the EDA report.

## Key Findings

- **Total Sales:** $6.18M | **Total Profit:** $1.61M (~26% margin)
- Sales are evenly distributed across all three categories — no single category dominates
- All categories and states are profitable; no loss-making segments in the dataset
- Tables, Sofas, and Electronic Games are top performers by both sales and quantity
- New York, Florida, and California lead by state sales
- Debit Card and Credit Card are the most-used payment methods

See the full report in `/report` for detailed answers to all 8 business questions.

## Dashboard

The interactive dashboard (`/dashboard/Sales_Dashboard) includes:
- KPI cards for Sales, Profit, Orders, and Units
- Filterable views by Category, State, Payment Mode, and Year
- Sales & profit trend, sub-category breakdowns, and top customer rankings

To view it, download the file and open it in any web browser — no installation required.

A Power BI (.pbix) version of the dashboard was also built as part of this project.
