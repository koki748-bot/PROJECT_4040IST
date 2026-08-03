# PROJECT_4040IST
# Retail Sales Decision Support System (DSS)

# Project Overview
The primary goal of this project is to build an interactive, data-driven Decision Support System that addresses key operational and strategic challenges in retail. Specifically, it resolves issues related to heavy revenue dependency on a single geographic market, inventory management and stockout risks, and low Average Order Value (AOV)

# Problem Statement
The online retail enterprise lacks an integrated, data-driven optimization strategy for marketing spend, customer retention, and regional inventory allocation, resulting in recurring stockouts and sub-optimal overall revenue.

# Dataset Information
1.Source: [UCI Machine Learning Repository — *Online Retail II* dataset.]

2.size: Minimum 5,000+ records

3.Description: Contains transaction records, including sales volume, unit prices, product 4.descriptions, invoice dates, and geographical locations.

# Data Cleaning & Transformation Process
1.Workbook Merging: Combined worksheets from Year 2009–2010 and Year 2010–2011 into a single consolidated dataset.

2.Missing Value Handling: Dropped records with null Customer ID or Description fields.

3.Transaction Filtering: Filtered out canceled orders (invoices beginning with C) and removed duplicate records.

4.Anomalies Removal: Stripped transactions containing non-positive quantities or invalid unit prices.


# Dashboard Architecture & Visual Features
 The Power BI report contains two interactive pages totaling 12 visual components:

# Page 1: Executive Overview & Geographic Sales
KPI Cards (3): Total Sales Measure, Average Order Value, Active Customer Count.

Slicers (2): Country (Checkbox dropdown) and InvoiceDate (Timeline slider).

Charts (2): 
Chart: Total Sales Measure by InvoiceDate
Clustered Bar Chart: Total Sales Measure by Country

# Page 2: Product & Inventory Deep-Dive
KPI Cards (2): Total Items Sold , Average Basket Size .

Visuals (3):
Clustered Column Chart: Sum of Quantity by Description (Top-performing items)
Scatter Plot: Sum of Price vs. Sum of Quantity (Price elasticity matrix)
Matrix View: Granular lookup of Sum of Price, Sum of Quantity, and Sum of Total Sales by product description.

# Interactive Features
Global Slicers: Dynamic updates across all visuals when filtering by country or timeline.

Cross-Filtering: Selecting a country bar highlights its specific sales trajectory over time.

# Dashboard Screenshots
Sales Overview Page: 
<img width="704" height="386" alt="page1" src="https://github.com/user-attachments/assets/e9748278-642e-4770-8d45-85fea62a01f8" />

Product Performance Page: 
<img width="764" height="431" alt="page2" src="https://github.com/user-attachments/assets/448fa948-333c-413f-985b-6648679d5e11" />



# Key Business Recommendations

1.United Kingdom generates the dominant majority of total sales.Core revenue source vulnerable to market shift if neglected.Increase UK marketing investment and protect inventory buffer. 

2.Top-performing items face high volume demand.High stockout risk resulting in missed revenue opportunities.Prioritize restocking triggers before stock levels hit critical thresholds.

3.Notable revenue fluctuations across different periods. Stock volatility and inefficient capital allocation.Implement predictive demand forecasting using historical time series. 

4.Low-selling stock keeping units (SKUs) present in portfolio.Tied-up working capital and reduced warehouse efficiency.Discount, bundle, or discontinue under-performing SKUs. 

5.Average Order Value stands at £469.98. Opportunity to scale revenue per transaction.Introduce cross-selling strategies and complementary product bundling. 

Estimated Impact: Implementation of the prescriptive framework holds the potential to generate approximately £3.2M in additional revenue



# github collaboration
team members and roles:
Rose chiyamwe: Data Acquisition, Cleaning and Python Pipeline setup (rose-data-cleaning branch).
Koki kyalo: Analytics, Power BI Dashboard development and visuals (feature/analytics-and-dashboard branch).
Joy mwaura: Decision Framework,and documentation (joy-decision-framework branch).

repository summary:
Branches: main, rose-data-cleaning, feature/analytics-and-dashboard, joy-decision-framework
Workflow: Each member created feature branches, completed commits, opened Pull Requests, reviewed peer code, and merged updates into the primary branch.


# Installation & Setup Instructions
Clone this repository:
   ```bash
git clone [https://github.com/koki748-bot/PROJECT_4040IST.git](https://github.com/koki748-bot/PROJECT_4040IST.git)
cd PROJECT_4040IST
```


