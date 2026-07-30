# AdventureWorks Excel Sales Analysis using Power BI

## Project Overview

This project demonstrates how Microsoft Power BI Desktop can be used to analyze sales data from an Excel workbook. The Excel file was prepared, cleaned, and transformed before being imported into Power BI. Interactive visualizations were then created to help business analysts understand sales performance by territory, country, product, and category.


# Objectives

* Prepare and optimize the Excel file for reporting.
* Import the Adventure Sales Excel file into Power BI Desktop.
* Perform data type transformations.
* Create interactive visualizations for business insights.
* Save the completed report as **AdventureWorks Excel.pbix**.


# Tools Used

* Microsoft Power BI Desktop
* Microsoft Excel

# Dataset

**Data Source:** Adventure Sales Excel File

The Sales table was imported into Power BI after formatting and data transformation.

# Tasks Performed

## 1. Optimized the Excel File

Reduced the file size by formatting the worksheet and removing unnecessary formatting.

## 2. Changed Cell Style

Applied the **Normal** cell style to maintain consistency and improve file performance.

## 3. Converted Data into a Table

Converted the dataset into an Excel Table to improve data organization and simplify importing into Power BI.

## 4. Imported Excel File

Imported the Adventure Sales Excel workbook into Power BI Desktop.


## 5. Converted Date Columns

Changed the following columns to the **Date** data type:

* OrderDate
* DueDate
* ShipDate



## 6. Converted Currency Columns

Formatted the following columns using the **US Dollar ($)** currency type:

* StandardCost
* SalesAmount
* TaxAmt



## 7. Loaded Sales Table

Loaded the Sales table into Power BI Desktop for report creation.



# Visualizations Created

## Sales by Sales Territory Group

**Visual:** Column Chart

* **Axis:** SalesTerritoryGroup
* **Values:** SalesAmount

Purpose:
To compare sales performance across different sales territory groups.



## Sales by Country

**Visual:** Map

* **Location:** SalesTerritoryCountry
* **Bubble Size:** SalesAmount

Purpose:
To visualize geographical sales distribution across countries.


## Top 10 Products by Sales

**Visual:** Bar Chart

* **Axis:** Product Name
* **Values:** SalesAmount

Applied a **Top N filter** to display only the top 10 products based on SalesAmount.

Purpose:
To identify the highest revenue-generating products.



## Product Distribution by Category

**Visual:** Pie Chart

* **Legend:** Product Category
* **Values:** SalesAmount

Purpose:
To analyze the contribution of each product category to overall sales.



# Dashboard Features

* Clean and optimized data model
* Correct data type transformations
* Currency formatting using US Dollar
* Interactive visualizations
* Geographic sales analysis
* Product performance analysis
* Category-wise sales distribution



# Output

**Report Name:**

AdventureWorks Excel.pbix



# Conclusion

This Power BI report demonstrates the complete workflow of preparing Excel data, performing data transformations, and creating interactive dashboards for business reporting. The visualizations provide valuable insights into sales performance across territories, countries, products, and categories, enabling better business decision-making.

