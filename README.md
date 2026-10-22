# E-commerce Sales Performance Dashboard | Power BI
 ## 1. Project Overview
The purpose of this project is to analyze e-commerce sales data, monitor business performance, evaluate profitability, and provide actionable insights to support data-driven decision-making.
## 2. Project Objectives
The main objectives of this project are to:
- Analyze overall sales performance and profitability.
- Calculate and monitor essential business KPIs.
- Identify high-performing and low-performing products.
- Evaluate sales and profit by product category.
- Compare performance across regions.
- Analyze sales trends over time.
- Monitor customer activity and order performance.
- Present business insights through an interactive dashboard.
## 3. Tools and Technologies
- Microsoft Power BI Desktop for Data modeling, DAX, and dashboard development Power Query	
- Power Query for Data cleaning and transformation
- DAX (Data Analysis Expressions) for KPI calculations and analytical measures 
- CSV / Excel for Data storage and input

## 4. Data Cleaning and Transformation


1.	Importing the dataset into Power BI Desktop.
2.	Checking column names and data types.
3.	Converting order dates to the Date data type.
4.	Converting quantities to whole numbers and financial fields to numeric types.
5.	Removing unnecessary spaces and cleaning text values.-
6.	Checking missing values, errors, and duplicate records.
7.	Validating sales, cost, and profit calculations.
8.	Reviewing negative or otherwise invalid values.
9.	Creating a calendar table for time-based analysis.
10.	Establishing relationships between the calendar table and the sales table.

## 6. Key Performance Indicators (KPIs)
- Total Sales
- Gross Profit
- Profit Margin
- Units Sold
- Total Orders

7. Dashboard Design and Visualizations
<a href="ttps://github.com/tolossa320/salas_data_analysis/blob/main/E-COMMERCE.jpg">
                Projects</a
              >

The dashboard presents business performance through interactive visuals.
Visualization	Purpose
KPI cards	Display total sales, gross profit, profit margin, units sold, and total orders
Line chart	Analyze sales trends over time
Bar chart	Compare gross profit by product
Column chart	Compare sales across product categories
Bar chart	Evaluate sales by region
Donut chart	Show the distribution of sales by channel
Product performance table	Compare sales, costs, profit, units, and margin
Slicers	Filter results by year, month, category, region, and sales channel
Interactive Features
The dashboard is designed to allow users to:
•	Filter results by reporting period.
•	Compare products and categories.
•	Explore regional performance.
•	Analyze sales channel contribution.
•	Review changes in KPI values when filters are applied.
9. Business Questions Addressed
The dashboard helps answer important business questions, including:
1.	How much total sales revenue has the business generated?
2.	What is the gross profit and gross profit margin?
3.	How many units have been sold?
4.	How many distinct orders and customers are represented?
5.	Which products generate the highest sales and gross profit?
6.	Which categories contribute most to total revenue?
7.	Which regions generate the strongest sales performance?
8.	Which sales channels contribute most to revenue?
9.	How do sales change over time?
10.	What opportunities exist to improve profitability and sales performance?
9. Business Insights and Recommendations
The dashboard can support the following analytical activities:
•	Product performance: Identify products with high revenue, strong profit, or weak profitability.
•	Category analysis: Determine which categories contribute most to overall sales.
•	Regional analysis: Identify regions with stronger or weaker sales performance.
•	Channel analysis: Compare website, mobile app, and marketplace sales.
•	Profitability analysis: Investigate products with low margins and review their pricing and costs.
•	Sales trend analysis: Identify periods of increased or decreased demand.
•	Customer analysis: Monitor distinct customers and average order value.
Recommended Business Actions
Based on the results of the actual dataset, the business could consider:
1.	Prioritizing profitable products in marketing campaigns.
2.	Reviewing costs and pricing for low-margin products.
3.	Improving marketing activities in underperforming regions.
4.	Comparing the effectiveness of different sales channels.
5.	Using sales trends to support inventory and purchasing decisions.
6.	Monitoring KPIs regularly to identify changes in business performance.
These are analytical recommendations rather than confirmed findings. Specific conclusions should be made only after examining the actual dashboard results.
10. Conclusion
The E-commerce Sales Performance Dashboard provides an interactive approach to analyzing sales, profitability, products, customers, regions, and sales channels using Power BI.
By combining data cleaning, data modeling, DAX measures, and visual analytics, the project transforms transaction data into information that can support business planning and decision-making.
The project also demonstrates practical capabilities in data analysis and business intelligence, including KPI development, time-based analysis, data visualization, and analytical reporting.
Future improvements could include connecting the report to a live database, configuring scheduled data refresh through Power BI Service, adding customer retention analysis, and developing more advanced forecasting measures.
11. Future Improvements
Potential enhancements include:
•	Connecting to a MySQL or SQL Server database.
•	Configuring scheduled refresh in Power BI Service.
•	Adding customer segmentation and repeat-purchase analysis.
•	Creating sales and profit forecasts.
•	Developing drill-through pages for detailed product analysis.
•	Adding inventory and stock performance metrics.
•	Improving data validation and automated refresh monitoring.
12. Project Structure
ecommerce-powerbi-dashboard/
│
├── README.md
├── ecommerce_sales_sample.csv
├── DAX_Measures.txt
├── BUILD_CHECKLIST.md
├── Ecommerce_Sales_Dashboard.pbix
└── screenshots/
    └── dashboard_overview.png
The Power BI file and screenshot should be added after the dashboard has been created. Do not include confidential company records, customer personal information, database credentials, or passwords.
13. How to Use This Project
1.	Download or clone this repository.
2.	Open Power BI Desktop.
3.	Import the CSV dataset.
4.	Clean and transform the data in Power Query.
5.	Create the calendar table and required relationships.
6.	Add the DAX measures documented in this repository.
7.	Build the recommended dashboard visuals.
8.	Validate the KPI results against the source data.
9.	Save the report as Ecommerce_Sales_Dashboard.pbix.
10.	Upload the report and dashboard screenshots to GitHub, subject to file-size and data-sharing restrictions.
14. Author
Tolossa Kenaw
Data Analytics | Power BI | SQL | Database Management
This project is part of my portfolio to demonstrate my skills in data analysis, business intelligence, data visualization, and data-driven decision-making.
15. License and Data Disclaimer
This project is intended for educational, portfolio, and demonstration purposes.
Ensure that any real business data used in the project is authorized for analysis and publication. Synthetic sample data should not be presented as actual business performance.
If a license is added to this repository, follow the terms specified in that license.
Recommended GitHub repository structure
Use this structure when uploading your project:
ecommerce-powerbi-dashboard/
├── README.md
├── ecommerce_sales_sample.csv
├── DAX_Measures.txt
├── BUILD_CHECKLIST.md
├── Ecommerce_Sales_Dashboard.pbix
└── screenshots/
    └── dashboard_overview.png
Before publishing: replace any placeholder descriptions with your actual findings, add a screenshot of your completed dashboard, and verify that the totals in your Power BI report match your source data.

    └── dashboard.png
