# Day 15 – Power BI Dashboard

## Project Overview

This project is a Power BI dashboard built using the Day 14 Capstone Customers and Orders data.

The dashboard focuses on analyzing **sales and profitability across regions, segments, and categories** to identify the key drivers of overall business performance.

## Dashboard Story

**Analyze sales and profitability across regions, segments, and categories to identify the key drivers of overall business performance.**

## Dashboard Features

### KPI Cards

The dashboard includes four key performance indicators:

* **Total Sales**
* **Total Profit**
* **Profit Margin %**
* **Order Count**

### Visualizations

The dashboard contains multiple visuals to analyze business performance, including:

* Sales by Region
* Profit by Region
* Sales Trend
* Sales by Category
* Profit by Category

Each visual supports the overall sales and profitability analysis.

### Slicers

The dashboard provides interactive slicers for:

* **Region**
* **Segment**

These slicers allow users to dynamically filter the dashboard and analyze different parts of the business.

## Drill-Through

A **Region Details** drill-through page is included.

Users can select a region from the dashboard and drill through to view detailed order-level information for that selected region.

This provides a more detailed view of the underlying orders contributing to the regional performance.

## Data Model

The dashboard uses the Capstone Customers and Orders datasets from Day 14.

The **Customers–Orders relationship** is maintained in the Power BI data model, allowing customer information and order information to be analyzed together.

## Verification

The dashboard values were cross-checked using Python.

For verification, the data was filtered for the **North region** and the following values were calculated:

* Total Sales
* Total Profit
* Order Count

The calculated values were compared with the corresponding values displayed in the Power BI dashboard.

## Tools Used

* Power BI
* Python
* Pandas
* CSV datasets

## File

`day15_powerbi_dashboard.pbix`

## Learning Objectives Covered

This project covers:

* Slicers and filters
* Interactive visuals and cross-filtering
* KPI cards
* Dashboard layout and design
* Drill-through pages
* Data model relationships
* Business performance analysis

## Conclusion

The dashboard provides an interactive overview of sales and profitability and allows users to move from high-level KPIs to regional and order-level details through filtering and drill-through functionality.

##Author:
Nikhil Chougale
