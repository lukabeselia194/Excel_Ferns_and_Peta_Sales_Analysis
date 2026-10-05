# 📊 Sales Analysis Dashboard
An interactive Sales Analysis Dashboard developed in Microsoft Excel using Power Query, Pivot Tables, Pivot Charts, and Slicers to transform raw sales data into actionable business insights. The dashboard provides executives and business stakeholders with a comprehensive overview of sales performance through dynamic KPIs and interactive visualizations.

# 📌 Project Overview
This project demonstrates the complete data analysis workflow—from data preparation to dashboard development. Raw sales data was cleaned, transformed, and modeled using Power Query, then visualized through an interactive Excel dashboard designed to support strategic business decisions.

The dashboard enables users to monitor key performance indicators, analyze sales trends, evaluate product performance, and identify customer purchasing patterns using dynamic filters and visual reports.

# 📊 Dashboard Preview
![Dashboard](https://github.com/lukabeselia194/Excel_Ferns_and_Peta_Sales_Analysis/blob/main/Dashboard%20Preview.png)

# 📈 Key Performance Indicators
| Metric   | Value    |
| -------- | -------- |
| Total Orders    | 1000 |
| Total Revenue  | £3,520,984 | 
| Average Customer Spending | £3,520.98 |
| Average Delivery Time | 5.53 Days |

# 💡 Insights
### 1. Revenue is highly seasonal
Valentine's Day, Holi, Raksha Bandhan and Diwali each have a ~10-day order window. Together they bring in ₹18.5L = 52.6% of revenue (520 of 1,000 orders).
Festival days average ~₹46,300 per day vs ~₹5,100 on other days (about 9x).
Four months (Feb, Mar, Aug, Nov) make up 68% of annual revenue. Every other month is a flat ₹1.4–1.6L, and January is the weakest at ₹95K (34 orders).
### 2. Raksha Bandhan is the most valuable festival; Diwali has the most headroom
Raksha Bandhan: ₹6.32L in 10 days (highest, ~₹63K/day) with the highest average order (₹4,785, 75% above Birthday's ₹2,740).
Diwali is just 9% of revenue (~₹31K/day), about half of Holi and Raksha Bandhan on a per-day basis.
Valentine's Day has the lowest average order of the festivals (₹2,937), an upselling opportunity.
### 3. Delivery timing is an operational gap
Using the actual 2023 festival dates (Feb 14, Mar 8, Aug 30, Nov 12), 238 of 520 festival orders (45.8%) have a delivery date after the festival (Valentine's 45%, Holi 47%, Raksha Bandhan 49%, Diwali 40%).
Delivery time is spread evenly from 1 to 10 days (avg 5.53; 32% of orders take 8+ days) and is unrelated to order value or quantity (correlation 0.01 and 0.00) and nearly identical across occasions (4.9–5.8 days).
Caveat: the data has no customer-requested delivery date, so this is inferred from the festival calendar.
### 4. Category and product performance
Colors is the largest category (₹10.06L, 29%), but Soft Toys earns the most per product (₹74K per product vs ₹26.5K for Plants) and Sweets is next (₹61K).
Plants, Mugs and Cake together contribute only 21% of revenue.
### 5. What drives order value
Quantity per order is the same across categories (~3). Category average order value follows item price, not volume (Soft Toys ₹4,463 vs Plants ₹2,144).
Orders are spread evenly across quantities 1–5, but 5-unit orders produce 36% of revenue.
Products priced ₹1,500–2,000 are 33% of orders but 50% of revenue; items under ₹500 give only 4%.
### 6. What the data does not show
No concentration risk: the top 10 customers are 16% of revenue, and the best product (Magnam Set) is 3.5%.
No gender effect: average order ₹3,517 (male) vs ₹3,525 (female).
No strong time-of-day pattern: orders arrive around the clock, and no hour exceeds 5% of revenue.
Geography is dispersed: orders ship to 301 locations, the busiest with only 9 orders. Only 0.1% of orders ship to the customer's registered city, consistent with gifting to others.

# 🚀 Features
- 📈 Executive KPI Dashboard
- 🔄 Automated data cleaning and transformation with Power Query
- 📅 Interactive date filters
- 🎉 Revenue by Occasion
- 🛍️ Revenue by Product Category
- ⏰ Revenue by Order Time
- 📆 Monthly Revenue Trends
- 🏆 Top 5 Products by Revenue
- 🌍 Top 10 Cities by Orders
- 💰 Average Customer Spending
- 🚚 Average Order-to-Delivery Time

# 🛠️ Tech Stack
- Microsoft Excel
- Power Query
- Pivot Tables
- Pivot Charts
- Slicers & Timelines
- Calculated Fields & KPIs
- Data Visualization

# 🔄 Data Analysis Workflow
### 1) Data Collection
  - Imported raw sales data into Excel.
### 2) Data Cleaning & Transformation
  - Cleaned and transformed the dataset using Power Query.
  - Handled inconsistent values and formatted data types.
  - Created additional columns required for analysis.
### 3) Data Modeling
  - Organized the cleaned data into an analysis-ready structure.
### 4) Data Analysis
  - Built Pivot Tables to summarize key business metrics.
  - Created KPIs to monitor overall business performance.
### 5) Data Visualization
  - Designed an interactive dashboard using Pivot Charts, KPI cards, and slicers.
### 6) Business Insights
  - Identified trends across products, occasions, cities, and time periods to support decision-making.


# ❓ Business Questions Answered
- Which occasions generate the highest revenue?
- Which product categories perform best?
- Which products contribute the most revenue?
- Which cities generate the highest number of orders?
- During which hours do customers purchase the most?
- How does revenue change throughout the year?
- What is the average customer spending?
- How efficient is the delivery process?

# 📚 Skills Demonstrated
- Data Cleaning
- Data Transformation
- Power Query (ETL)
- Data Modeling
- Pivot Tables
- KPI Design
- Data Visualization
