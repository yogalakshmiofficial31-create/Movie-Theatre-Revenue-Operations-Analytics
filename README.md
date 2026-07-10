# 🎬 CineMax Multiplex Revenue & Operations Analytics

## 📌 Project Overview

This project is an end-to-end Business Intelligence solution developed using **Power BI**. It analyzes movie ticket sales and theatre operations to help management monitor revenue, occupancy, customer behavior, promotion effectiveness, and overall business performance through interactive dashboards.

---

## 🎯 Business Objective

Build a centralized Power BI dashboard that transforms raw movie theatre data into meaningful business insights using:

- Power Query (ETL)
- Star Schema Data Modeling
- DAX Measures
- Interactive Dashboards
- Business Storytelling

---

## 🏢 Business Background

CineMax Multiplex operates multiple theatres across Tamil Nadu. Despite increasing ticket sales, management lacks visibility into:

- Movie performance
- Theatre occupancy
- Revenue trends
- Customer booking behavior
- Food & Beverage sales
- Promotion effectiveness
- Operational efficiency

This dashboard helps stakeholders make data-driven business decisions.

---

## ❓Business Questions

- Which movies generate the highest revenue?
- Which theatres have the highest occupancy?
- What are the peak show timings?
- How do weekday and weekend revenues compare?
- Which genres perform best?
- What is the impact of promotions on ticket sales?
- How much revenue comes from Food & Beverage sales?
- What operational improvements can increase occupancy and profitability?

---

## 📂 Dataset

### Dimension Tables

- Dim_Category_Movie
- Dim_Customer_Movie
- Dim_Date_Movie
- Dim_Movie
- Dim_Promotion_Movie
- Dim_Screen
- Dim_Show
- Dim_Theatre

### Fact Table

- Fact_Ticket_Sales_5000

---

## 🧹 Data Cleaning (Power Query)

The following transformations were performed:

- Imported multiple Excel datasets
- Removed duplicate records
- Validated primary keys
- Verified data types
- Handled missing values
- Renamed tables and columns
- Cleaned date formats
- Checked data consistency
- Created relationships

---

## ⭐ Data Model

A Star Schema was implemented.

**Fact Table**

- Fact_Ticket_Sales

**Dimension Tables**

- Category
- Customer
- Date
- Movie
- Promotion
- Screen
- Show
- Theatre

---

## 📊 DAX Measures

- Total Revenue
- Total Tickets Sold
- Total Customers
- Total Bookings
- Food Revenue
- Average Ticket Price
- Average Occupancy %
- Average Customer Rating
- Confirmed Bookings
- Cancelled Bookings
- Refunded Bookings
- YTD Sales
- MTD Sales

---

## 📈 Dashboard Pages

### 📄 Executive Dashboard

- KPI Cards
- Revenue by Movie
- Revenue by Theatre
- Monthly Revenue Trend
- Revenue by Genre
- Interactive Slicers

### 📄 Revenue Analysis

- Revenue by Language
- Revenue by Theatre
- Revenue by Director
- Revenue by Genre

### 📄 Operations Dashboard

- Theatre Occupancy
- Peak Show Timings
- Weekday vs Weekend Revenue
- Booking Status Analysis
- Screen Performance

### 📄 Customer & Promotion Dashboard

- Promotion Analysis
- Booking Channel Analysis
- Payment Mode Analysis
- Membership Analysis
- Food & Beverage Revenue
- Customer Rating Analysis

---

## 📌 Key KPIs

- 💰 Total Revenue
- 🎟 Total Tickets Sold
- 👥 Total Customers
- 🎫 Total Bookings
- 🍿 Food Revenue
- 💺 Average Occupancy %
- ⭐ Average Customer Rating
- ✅ Confirmed Bookings
- ❌ Cancelled Bookings
- 💵 Refunded Bookings
- 📅 YTD Sales
- 📅 MTD Sales

---

## 💡 Business Insights

- Identified the highest revenue-generating movies and theatres.
- Analyzed occupancy trends across theatres.
- Compared weekday and weekend revenue performance.
- Evaluated promotion effectiveness on ticket sales.
- Measured Food & Beverage contribution to overall revenue.
- Analyzed customer booking channels and payment preferences.

---

## 📌 Business Recommendations

- Increase shows for high-performing movies.
- Introduce targeted promotions during weekdays.
- Expand Food & Beverage offerings.
- Improve occupancy through optimized show scheduling.
- Strengthen customer loyalty programs.
- Focus marketing efforts on top-performing genres and theatres.

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Star Schema Data Modeling

---

## 📁 Project Structure

```text
CineMax-Multiplex-Revenue-Analytics/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── powerbi/
│   └── CineMax_Multiplex_Analytics.pbix
│
├── dashboard/
│   ├── Executive_Dashboard.png
│   ├── Revenue_Analysis.png
│   ├── Operations_Dashboard.png
│   └── Customer_Promotion_Dashboard.png
│
├── presentation/
│   └── CineMax_Project_Presentation.pptx
│
├── documentation/
│   └── README.md
│
└── LICENSE
```

---

## 🚀 Skills Demonstrated

- Power BI
- Power Query
- Data Cleaning
- Data Modeling
- Star Schema
- DAX
- KPI Development
- Dashboard Design
- Business Intelligence
- Data Visualization
- Business Analysis

---

## 👩‍💻 Author

**Yogalakshmi M**

**Aspiring Data Analyst**

**Skills:** Power BI | SQL | Python | Excel | Data Analytics | Business Intelligence

---

## ⭐ Project Outcome

This project demonstrates an end-to-end Business Intelligence workflow, from data cleaning and transformation to dashboard development and business storytelling using Power BI. It showcases practical skills in Power Query, DAX, Star Schema modeling, KPI development, and interactive dashboard design.