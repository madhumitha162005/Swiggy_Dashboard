🍔 Swiggy Power BI Dashboard Analysis

An interactive Power BI dashboard project for analyzing food-delivery order performance, revenue, restaurants, payment methods, ratings, cuisines, and order status.

Project type: Data Analytics / Business Intelligence
Tool: Microsoft Power BI
Report: Swiggy Dashboard Powerbi.pbix

📌 Project Overview

The Swiggy Power BI Dashboard converts order and restaurant data into an interactive one-page analytical report.

The dashboard focuses on:

Revenue performance

Order volume

Average Order Value

Cancellation Rate

Monthly revenue trends

Restaurant-level revenue

Payment-method distribution

Restaurant rating vs Average Order Value

Cuisine-level order status

City, cuisine, payment, status and date filtering

🎯 Objectives

Monitor key business KPIs in one place.

Understand revenue and order trends over time.

Analyze restaurant-level performance.

Explore payment behavior.

Study the relationship between restaurant ratings and order economics.

Enable interactive filtering for deeper analysis.

📊 Dashboard KPIs

KPI

Purpose

Total Revenue

Overall revenue represented by the report data

Total Orders

Overall order volume

Average Order Value

Average revenue value per order

Cancellation Rate

Rate of orders classified as cancelled

📈 Dashboard Visuals

The uploaded PBIX contains one report page with:

4 KPI Cards

Line Chart — Monthly Net Revenue

Clustered Bar Chart — Restaurant Revenue

Donut Chart — Orders by Payment Method

Scatter Chart — Restaurant Rating vs Average Order Value

Column Chart — Orders by Cuisine and Order Status

5 Slicers — City, Cuisine, Payment Method, Order Status and Order Date

Swiggy-themed image assets and dashboard title

🧩 Data Model

The PBIX model contains these entities:

Orders

Restaurants

Customers

Dax Measures

Key fields referenced by the report

Orders

Order Month

Net Revenue

Payment Method

Order Status

Order Date

Restaurants

Restaurant Name

Rating

Cuisine

City

Dax Measures

Total Revenue

Total Orders

Average Order Value

Cancellation Rate

The exact source-dataset provenance and exact DAX expressions are not claimed here because they are not reliably exposed by the PBIX report-layout metadata.

🛠️ Tools & Technologies

Microsoft Power BI Desktop

Power Query

DAX

Data Modeling

Data Visualization

Business Intelligence

🔄 Analytical Flow

Source Data
    ↓
Data Ingestion / Transformation
    ↓
Power BI Semantic Model
    ↓
Orders + Restaurants + Customers
    ↓
DAX Measures
    ↓
Interactive Visualizations
    ↓
Dashboard Analysis

📁 Repository Structure

Swiggy-PowerBI-Analysis/
│
├── README.md
│
├── PDD/
│   └── Swiggy_PowerBI_PDD.docx
│
├── SDD/
│   └── Swiggy_PowerBI_SDD.docx
│
├── PowerBI/
│   └── Swiggy Dashboard Powerbi.pbix
│
├── Dataset/
│   └── Swiggy_Dataset.xlsx
│
└── Screenshots/
    └── Swiggy_Dashboard.png

Add the Dataset folder only if the dataset is legally shareable and does not contain confidential or personal information.

🧪 Validation Checklist

KPI cards configured

Monthly revenue trend configured

Restaurant revenue visual configured

Payment method analysis configured

Rating vs AOV analysis configured

Cuisine and order-status analysis configured

City slicer configured

Cuisine slicer configured

Payment Method slicer configured

Order Status slicer configured

Order Date slicer configured

📚 Documentation

PDD: PDD/Swiggy_PowerBI_PDD.docx — business requirements, objectives, scope, KPIs and functional requirements.

SDD: SDD/Swiggy_PowerBI_SDD.docx — technical architecture, model components, visual inventory, measure design, testing and deployment.

⚠️ Disclaimer

This is a Power BI analytics portfolio/project implementation. It should not be represented as an official internal Swiggy dashboard or as live Swiggy corporate data unless the underlying data and authorization genuinely support that claim.

👩‍💻 Project Author

Madhumitha 
