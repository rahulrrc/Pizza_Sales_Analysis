Pizza-Sales-Data-Analysis

End-to-end pizza sales analytics project covering data exploration, SQL business analysis, and comprehensive reporting — built to identify sales trends, customer purchasing behavior, and revenue drivers.

Business Problem

Analyze pizza sales data to identify key performance indicators (KPIs), understand customer ordering patterns, and provide actionable insights to optimize inventory and increase profitability.

Key Result

Comprehensive analysis of pizza sales, identifying peak ordering times, best-selling pizza categories, and revenue generation metrics.
Full findings and recommendations: Pizza_Sales_Report_Insights.pdf and Pizza_Sales_Report_Overview.pdf

Tech Stack

| Stage | Tool |
| --- | --- |
| Data Source | Excel (`pizza sales data.xlsx`)

 |
| Business Analysis | SQL (`Pizza Query.sql`)

 |
| Reporting & Presentations | PowerPoint (`Pizza Sales Analysis.pptx`, `pizza sales stakeholder presentation.pptm`), PDF

 |

Project Workflow

Raw Excel Dataset → SQL (analysis & business queries) → PowerPoint (stakeholder presentations) → PDF (insights & overview reports)

Folder Structure

├── pizza sales data.xlsx                             # raw source data
├── Pizza Query.sql                                   # SQL business analysis queries
├── Pizza Sales Analysis.pptx                         # main analysis presentation
├── pizza sales stakeholder presentation.pptm         # presentation tailored for stakeholders
├── Pizza_Sales_Report_Overview.pdf                   # high-level overview report
├── Pizza_Sales_Report_Insights.pdf                   # detailed client-facing insights report
└── README.md                                         # project documentation

Data Model

Relational analysis performed directly on the pizza sales dataset, aggregating order details, pizza types, and sales records.

Data Cleaning Summary

Standardized date and time formats for accurate trend analysis
Checked for and handled any missing or null values in order records
Aggregated pizza categories, sizes, and pricing for accurate revenue calculations

Business Questions Answered

What is the total revenue and total number of pizza orders?
Which pizza sizes and categories generate the highest revenue?
What are the peak days and times for customer orders?
What are the best and worst-selling pizzas?
What is the average order value?
Full queries: Pizza Query.sql

Recommendations

Optimize inventory for top-selling pizzas and prepare staffing for peak ordering days/times.
Introduce targeted promotions or discounts during slow operational hours to boost sales.
Re-evaluate or phase out the worst-performing pizza variations to reduce ingredient waste.
Leverage the high-revenue pizza categories for future marketing campaigns.

Dashboard / Reporting

The project includes detailed static reports (`Pizza_Sales_Report_Overview.pdf`, `Pizza_Sales_Report_Insights.pdf`) and interactive slide decks (`Pizza Sales Analysis.pptx`, `pizza sales stakeholder presentation.pptm`) intended for stakeholder review and business strategy planning.

How to Reproduce

Data: Review the raw dataset in `pizza sales data.xlsx`.
SQL: Run `Pizza Query.sql` against the imported dataset in your SQL database to view the business queries.
Presentations: Open the PPTX, PPTM, and PDF files to view the final compiled insights and overview.

Author

Rahul M Ramchandani
Email: rahulramchand505@gmail.com
LinkedIn: Rahul M Ramchandani
