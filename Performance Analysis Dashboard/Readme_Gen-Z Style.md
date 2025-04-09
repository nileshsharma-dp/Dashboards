# Performance Report Dashboard (Plant Co.)

### 🔗 Dashboard Link : [View on Power BI](https://app.powerbi.com/reportEmbed?reportId=e2ef757d-735a-410f-84f4-8ef9d5b4b9d3&autoAuth=true&ctid=24474f92-a838-4e8c-8c75-c12918e3b160)

---

## Problem Statement

This dashboard helps **Plant Co.** track Gross Profit performance **Year-To-Date (YTD)** vs **Prior Year-To-Date (PYTD)**. It enables performance analysis across:

- **Countries**
- **Product categories**
- **Months**

This view supports strategic decision-making by identifying:

- Key drivers behind profit drops/gains.
- Time trends in performance.
- Profitable vs unprofitable accounts (based on GP% and absolute GP).
- Account segmentation by profitability.

**Current Status**: Gross Profit has dropped by **-5.5M**, with GP% at **39.8%** and YTD Sales at **1.4M**.

---

## Steps Followed

1. **Data Import**  
   Loaded sales data into Power BI Desktop.

2. **Data Cleaning**  
   Used Power Query to:
   - Clean and transform data.
   - Review column distribution and data types.

3. **Time Filtering**  
   Created slicers for:
   - Year (2023, 2024)
   - Metric type (Gross Profit, Sales, Quantity)

4. **KPI Cards Created**:
   - `S_YTD` (Sales YTD)
   - `S_PYTD` (Sales PYTD)
   - `YTD_vs_PYTD` (Variance)
   - `GP_%` (Gross Profit %)

5. **Waterfall Chart**  
   Visualizes YTD vs PYTD GP change by **month** and **country**.  
   - Green: Profit increased  
   - Red: Profit decreased  
   - Light Green: Totals  

6. **Combo Chart**  
   Gross Profit over months with comparison lines for YTD vs PYTD.

7. **Treemap**  
   Top 10 countries based on Gross Profit change.

8. **Scatter Plot**  
   Used for **Account Profitability Segmentation**:  
   - **X-axis**: Gross Profit  
   - **Y-axis**: GP%  
   - Size: Absolute Sales

9. **Toggle Slicer**  
   Users can switch between **Sales, Quantity, and GP** analysis.

10. **Design & Theme**  
    - High-contrast dark mode (Black + Neon Green)  
    - Bold visuals for stakeholder presentation

11. **Deployment**  
    Published to Power BI Service for sharing and collaboration.

---

## Key Insights

### 🧾 Yearly Performance
- **Sales (YTD)**: 1.4M  
- **Sales (PYTD)**: 6.9M  
- **Variance**:  -5.5M  
- **Gross Profit %**: 39.8%

### Monthly GP Change
- Sharp drop in **April (-0.53M)** and **May (-0.55M)**
- Recovery signs in **July, October, and November**
- Target months with consistent decline

### Top Performing Countries (GP↑)
| Rank | Country     | Change in GP |
|------|-------------|---------------|
| 1  | Hungary     | +25K          |
| 2  | Switzerland | +18K          |
| 3  | Costa Rica  | +15K          |
| 4  | UK          | +12K          |
| 5️  | Australia   | +10K          |

### Account Segmentation
- Majority of accounts fall within **30-50% GP%**
- A few accounts: **High GP but low volume**
- Others: **High volume, low margin** → need deeper pricing review

---

## Suggested Actions

- Deep-dive into Q2 (April–June) losses
- Audit pricing for low-margin, high-volume customers
- Focus on growth in Hungary, Switzerland, and UK
- Align sales strategy to improve YTD vs PYTD gap

---

## Dashboard Snapshot

![Dashboard](https://github.com/nileshsharma-dp/Dashboards/blob/main/Performance%20Analysis%20Dashboard/Images/Dashboard.png)

---
