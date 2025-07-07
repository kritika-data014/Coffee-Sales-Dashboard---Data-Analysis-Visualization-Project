# Coffee-Sales-Dashboard---Data-Analysis-Visualization-Project

🧭 **Project Overview**
   
An interactive Excel dashboard presenting coffee sales insights—covering total revenue, product performance, geography, customer ranking—using standard Excel features (XLOOKUP, pivot tables, slicers, charts).

🎯 **Purpose:** 

Showcase data-cleaning, formula building, analysis, and dashboard design skills for a clean portfolio presentation.

🗂️**Understanding the Dataset**

Based on three related tables :

a) **Orders:** Transaction ID, Customer ID, Product ID, quantity, date, time.

b) **Customers:** Customer ID with name, email, country, loyalty-status.

c) **Products:** Product ID with coffee type (Arabica/Robusta/…), roast (L, M, D), size, unit price, profit margin

❓**Key Business Questions**

Use cases and analytical scenarios include:

a) **Revenue trends:** How did sales evolve over months/years?

b) **Product performance:** Which coffee types, roasts, sizes drive revenue?

c) **Geographic demand:** Which countries/top regions show strongest sales?

d) **Customer behavior:** Who are the top spenders? Segment by loyalty?

e) **Filtering needs:** Enable drill-down by time range, product type, roast, size, country, loyalty status via interactive slicers.

🛠️**Tools Used**

- **Microsoft Excel:** For data cleaning, processing, and dashboard creation.

🛠️**Method**

1) **Import & Clean Data**

- Load the three tables into Excel.
- Check duplicates, missing values using conditional formatting; clean dates/prices

2) **Enhance via Formulas**

 - _XLOOKUP_: Merge customer info (name, email, country) into Orders
 - _INDEX‑MATCH_: Pull product details (coffee type, roast, size, price)
 - _IF statements_: Expand codes (“Rob”) into full names (“Robusta”), categorize roast types.
 - _Calculated columns_: Revenue = unit price × quantity; plus derived Month, Year, Weekday or Time‑Buckets.

3) **Summarize using Pivot Tables**

 - Pivot for total revenue over time, revenue by country, top products, top 5 customers

4) **Visualize with Excel Charts**

 - Create line charts, bar charts, pie charts.
 - Embed slicers and timeline to interactively filter by coffee type, roast, size, loyalty, date

5) **Dashboard Design**

 - Build a clean dashboard sheet: KPIs, trend-lines, key charts.
 - Align slicers and timeline at top for interactivity.
 - Use consistent color theme and layout balance.
  


