# 📊 Online Retail Data Visualization Project

## 📁 Project Overview
This project presents a detailed Power BI dashboard using the Online Retail Data Set, visualizing key business insights from 2011 transactional data. It helps stakeholders analyze revenue trends, customer behavior, product demand, and sales performance across countries.

## 📦 Dataset Used

File: Online Retail Data Set.xlsx
Content: Includes transactional data for a UK-based online retailer from December 2010 to December 2011.

## Key Columns:

InvoiceNo: Unique invoice number
StockCode: Product identifier
Description: Product name
Quantity: Units sold
InvoiceDate: Date of transaction
UnitPrice: Price per unit
CustomerID: Unique customer ID
Country: Country of the customer

## 📈 Power BI Visualizations

All visualizations were developed in Power BI Desktop. Visuals include:

1.Monthly Revenue for 2011
 Trend line of monthly sales revenue
2.Top 10 Revenue-Generating Countries (Excl. UK)
 Bar chart of countries by revenue and quantity sold
3.Sum of Quantity by Country
 Visual comparison of total product demand per country
4.Top 10 Customers by Revenue
 Customer segmentation based on total revenue
5.Country-wise Monthly Sales (Australia Example)
 Table with monthly quantity and revenue breakdown
6.Product Demand by Country (Excl. UK)
 Insights into which products were most popular outside the UK

## 🛠️ How to Use

1.Open the Online Retail Data Set.xlsx file in Power BI.
2.Clean and transform the data using Power Query:
   Remove nulls in CustomerID
   Filter for the year 2011
   Create new columns as needed: Revenue = Quantity * UnitPrice
3.Reproduce the visuals shown in Data visualization.pdf or customize your own. 

## 🔍 Insights Highlighted

- The United Kingdom was the top contributor to revenue and quantity.
- Netherlands, EIRE, Germany, France were leading international markets.
- Top customers generated over £300K+ in revenue collectively.
- Seasonal trends are evident, with Q4 showing revenue spikes.

## 📎 Files

- [Online Retail Data Set.xlsx](https://github.com/hrishi439/Data-Analysis-Dashboards/blob/main/Online%20Retail%20Data%20Set.xlsx)  – Raw data
- [Data visualization.pdf](https://github.com/hrishi439/Data-Analysis-Dashboards/blob/main/Data%20visualization.pdf) – Snapshot of Power BI report visuals
- README.md – Project documentation

## 📌 Requirements

- Power BI Desktop (Latest version recommended)
- Basic familiarity with DAX and Power Query
