[README (3).md](https://github.com/user-attachments/files/29395250/README.3.md)
# 📊 DecodeLabs Data Analytics Portfolio — Batch 2026

**Oluwabusola** | Data Analytics Intern  
*"I find the story hiding in your data — before it costs you revenue."*

---

## Overview

This repository contains all four projects completed during my DecodeLabs internship. Each project builds on the last, taking a single e-commerce orders dataset (~1,200 rows, 14 columns, Jan 2023–Jun 2025) from raw data all the way to an interactive dashboard.

| # | Project | Tool | Focus |
|---|---------|------|-------|
| 1 | [Data Cleaning](#project-1-data-cleaning) | Excel | Raw data → analysis-ready |
| 2 | [Exploratory Data Analysis](#project-2-exploratory-data-analysis) | Excel | Patterns & insights |
| 3 | [SQL Data Analysis](#project-3-sql-data-analysis) | MySQL Workbench | Structured querying |
| 4 | [Data Visualization](#project-4-data-visualization-dashboard) | Power BI | Storytelling dashboard |

---

## Dataset

**E-commerce Orders Dataset**
- ~1,200 rows · 14 columns
- Covers January 2023 – June 2025
- Fields include: Order ID, Order Date, Customer ID, Product Category, Order Value, Payment Method, Referral Channel, Coupon Used, Delivery Status, and more

---

## Project 1: Data Cleaning

**Tool:** Microsoft Excel

### Objective
Transform a messy raw dataset into a clean, analysis-ready file by identifying and resolving data quality issues.

### Steps Taken
- Removed duplicate rows
- Standardised inconsistent text entries (e.g. capitalisation, trailing spaces)
- Handled missing values across key columns
- Corrected data types (dates, currency, numerical fields)
- Validated column ranges and flagged anomalies

### Key Outcome
A clean dataset with consistent formatting, no duplicates, and reliable values across all 14 columns — ready for analysis.

---

## Project 2: Exploratory Data Analysis

**Tool:** Microsoft Excel (Pivot Tables, Charts)

### Objective
Explore the cleaned dataset to uncover trends, patterns, and business-relevant insights.

### Key Findings
- **~19.25% delivery rate** — the majority of orders are in other status categories
- **Cancelled orders have the highest average order value (~$1,105)** — high-value customers are walking away
- **Instagram is the top revenue-generating referral channel**
- **Coupon users spend more on average than non-coupon users** — promotions attract higher-value baskets

### Approach
- Built pivot tables to summarise data by status, channel, category, and time
- Created charts to visualise distributions and trends
- Documented observations and business implications for each finding

---

## Project 3: SQL Data Analysis

**Tool:** MySQL Workbench

### Objective
Query the dataset using SQL to answer specific business questions with precision and reproducibility.

### Queries Covered
- Total revenue and order volume by time period
- Top-performing product categories
- Referral channel revenue breakdown
- Delivery rate by order status
- Average order value by customer segment
- Coupon vs. non-coupon spend comparison
- Cancellation analysis by channel and category

### Notable Learning
> Empty cells imported from CSV may come in as empty strings rather than `NULL`. Queries on nullable columns required `OR column = ''` guards to return accurate results — discovered during the coupon analysis query.

### Key Outcome
A full set of documented SQL queries that reproduce every major finding from the EDA, with added precision and filtering capability.

---

## Project 4: Data Visualization Dashboard

**Tool:** Power BI (with DAX calculated columns)

### Objective
Build a stakeholder-ready dashboard that communicates the most important findings at a glance.

### Design Principles (DecodeLabs Guidelines)
- **Action titles** — every chart title states the insight, not just the metric
- **SCR framework** — Situation, Complication, Resolution structures the narrative
- **Data-ink ratio** — removed all chart junk; every element earns its place
- **5-second rule** — a viewer should grasp the key message within 5 seconds
- No 3D charts, no unnecessary gridlines, no decorative elements

### Dashboard Highlights
- Revenue by referral channel (Instagram leads)
- Order status distribution (delivery rate spotlight)
- Average order value by status (cancelled orders anomaly)
- Coupon vs. non-coupon spend comparison
- Monthly revenue trend (Jan 2023 – Jun 2025)

### Key Outcome
A single-page Power BI dashboard that tells a clear, decision-ready story from the data.

---

## Key Insights Across All Projects

| Finding | Implication |
|--------|-------------|
| ~19.25% delivery rate | Fulfilment process needs urgent review |
| Cancelled orders avg ~$1,105 AOV | High-value customers are the most at risk of churning |
| Instagram = top revenue channel | Double down on Instagram; audit underperforming channels |
| Coupon users spend more | Promotions are working — but need margin analysis |

---

## Tools & Skills Demonstrated

`Microsoft Excel` · `Pivot Tables` · `MySQL` · `SQL Querying` · `Power BI` · `DAX` · `Data Cleaning` · `EDA` · `Dashboard Design` · `Data Storytelling`

---

## Connect
www.linkedin.com/in/oluwabusola-oyenuga
