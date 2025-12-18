# Sales Dashboard Project Write-up
________________________________________
## Project Overview
This project aims to design an interactive Excel sales dashboard for an E-commerce company. The dashboard provides insights into sales performance across different product categories, months, and regions, enabling management to make data-driven decisions.
________________________________________
## Dataset Used
•	File: -<a href="https://github.com/suhaanbhadriofficial/Data_Analysis_Excel_Dashboard/blob/main/E-Commerce%20Dashboard%20dataset.xlsx">Dataset</a>
•	The dataset includes fields such as Order ID, Order Date, Ship Mode, Product Category, Product Name, Sales, Quantity, Discount, Profit, Shipping Cost, Order Priority, Customer details, Location (City, State, Country, Region), and Months.
________________________________________
## 1. Data Preparation
Sheet Name: Data (or original data sheet)
•	Imported the sales data and checked for blanks or duplicates.
•	Converted the range into an Excel Table for easy analysis (Ctrl + T).
________________________________________
## 2. Working Sheet
Sheet Name: Working
## A. Month-wise Sales and Profit Table
•	Created a Pivot Table:
o	Rows: Months
o	Values: Sales, Profit
o	Filter: Product Category (to enable dashboard interactivity)
•	This table allows quick analysis of sales and profit trends month by month.
## B. Region-wise Sales Table
•	Created another Pivot Table:
o	Rows: Region
o	Values: Sales
o	Filter: Product Category
•	This table shows which regions contribute the most to total sales.
________________________________________
## 3. Dashboard Sheet
Sheet Name: Dashboard
A. Product Category Control
•	Added a Combo Box  linked to Product Category:
o	Allows users to select a specific product category.
o	All charts and tables update automatically based on selection.
B. Month-wise Sales & Profit Chart
•	Created Column Charts based on the month-wise Pivot Table.
•	Visualizes trends over time for both sales and profit.
C. Region-wise Sales Chart
•	Created another Clustered Column Chart based on the region-wise Pivot Table.
•	Shows sales distribution across different regions.
D. Layout
•	The Combo Box is placed at the top for user selection.
•	Charts are placed below for a clear, easy-to-read summary.
•	Added appropriate titles and formatting for clarity.
________________________________________
## 4. Interactivity
•	Selecting a Product Category using the Combo Box dynamically updates all charts and tables on the dashboard.
•	Stakeholders can instantly view trends for any category, by month and by region.
________________________________________
## 5. Summary of Steps (Action Points)
1.	Imported and cleaned the E-Commerce dataset.
2.	Created Pivot Tables for month-wise and region-wise summaries in the Working sheet.
3.	Inserted a Combo Box to filter by Product Category.
4.	Built interactive charts for both analyses.
5.	Designed the dashboard with clear layout and interactive controls.
________________________________________
# Conclusion
The interactive dashboard allows management to:
•	Analyze sales and profit trends across months for each product category.
•	Identify top-performing regions.
•	Make informed, data-driven business decisions.
________________________________________
# File Structure Submitted:
•	Data: Raw dataset
•	Working: Pivot Tables for analysis
•	Dashboard: User controls and interactive charts
-<a href="https://github.com/suhaanbhadriofficial/Data_Analysis_Excel_Dashboard/blob/main/SALES%20DASHBOARD%20PROJECT.xlsx">Project</a>
![Dashboard Preview](https://github.com/suhaanbhadriofficial/Data_Analysis_Excel_Dashboard/blob/main/dashboard_screenshot.PNG)

