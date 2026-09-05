# Supply Chain Analytics Dashboard | Power BI

## Project Overview

This project focuses on analyzing supply chain operations using Microsoft Power BI. The dashboard brings together sales, inventory, production, procurement, shipment, supplier, product, and customer data in one place.

The goal is to understand business performance, identify operational trends, and provide useful insights that can support data-driven decision-making.

## Business Objective

The main objective of this project is to monitor key areas of the supply chain and answer important business questions such as:

- How much revenue and profit is being generated?
- Which products and suppliers are performing well?
- What is the current inventory position?
- How efficiently are shipments being delivered?
- How is production performing?
- Where are potential supply chain issues?

## Tools & Technologies

- **Power BI** – Dashboard development and data visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and KPI calculations
- **Data Modeling** – Relationships between fact and dimension tables
- **CSV** – Source data

## Dataset

The project uses multiple datasets representing different parts of the supply chain.

### Dimension Tables

- `dim_customer` – Customer information
- `dim_date` – Date and calendar information
- `dim_facility` – Facility information
- `dim_product` – Product details
- `dim_supplier` – Supplier information

### Fact Tables

- `fact_sales` – Sales and revenue transactions
- `fact_shipment` – Shipment and delivery information
- `fact_production` – Production-related data
- `fact_procurement` – Procurement transactions
- `fact_inventory` – Inventory and stock information

## Key Performance Indicators

The dashboard tracks the following KPIs to provide a clear view of overall supply chain performance:

- **Total Revenue** – Measures the total revenue generated from sales.
- **Total Profit** – Shows the overall profit generated across the business.
- **Profit Margin %** – Measures profitability relative to total revenue.
- **Total Shipments** – Tracks the total number of shipments processed.
- **Delivered Orders %** – Shows the percentage of shipments successfully delivered.
- **Inventory Level** – Provides visibility into available stock across facilities.
- **Production Quantity** – Tracks the total quantity produced.
- **Procurement Cost** – Measures the overall cost of procurement activities.
- **Perfect Order %** – Evaluates order performance based on delivery and quality requirements.

## Dashboard Features

The dashboard provides interactive analysis across different areas of the supply chain, including:

- Sales and revenue analysis
- Profit and margin analysis
- Shipment and delivery performance
- Inventory monitoring
- Production analysis
- Procurement analysis
- Supplier performance
- Product-level analysis
- Customer analysis
- Facility-level analysis
- Interactive filters and slicers
- KPI cards and visual reports

## Data Preparation

The data was prepared using Power Query before being used in the dashboard.

The main steps included:

1. Importing the source CSV files
2. Reviewing data types and column formats
3. Cleaning and transforming the data
4. Handling missing or inconsistent values where required
5. Creating relationships between tables
6. Building calculated measures using DAX
7. Designing the final interactive dashboard


