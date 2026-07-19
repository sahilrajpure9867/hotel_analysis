🏨 Hotel Revenue Analysis Dashboard
📌 Project Overview

The Hotel Revenue Analysis Dashboard is an end-to-end data analytics project designed to analyze hotel booking and revenue performance. The project focuses on transforming raw hotel booking data into meaningful business insights using Python, SQL, Power BI, and Excel. It enables hotel management to monitor key performance indicators (KPIs), identify revenue trends, analyze occupancy, and make data-driven decisions.

This project demonstrates the complete analytics workflow—from data cleaning and exploration to database querying and interactive dashboard creation.

🎯 Objectives
Analyze hotel booking and revenue performance.
Track occupancy and cancellation trends.
Identify high-performing hotels, cities, and booking platforms.
Measure customer behavior and booking patterns.
Create an interactive dashboard for business decision-making.
📂 Dataset

The dataset contains hotel booking and revenue information, including:

Hotel Name
Property ID
City
Room Category
Booking Date
Check-in Date
Check-out Date
Booking Platform
Booking Status
Revenue
ADR (Average Daily Rate)
Occupancy %
RevPAR
Realisation %
Cancellation %
Customer Rating
Capacity
Successful Bookings
🛠️ Tools & Technologies
Tool	Purpose
Python	Data Cleaning & EDA
Pandas	Data Manipulation
NumPy	Numerical Operations
Matplotlib	Data Visualization
SQL (PostgreSQL/MySQL)	Data Analysis
Power BI	Dashboard Development
Excel	Initial Data Inspection
Git & GitHub	Version Control
📊 Project Workflow
1. Data Collection

Collected hotel booking and revenue datasets from multiple CSV files.

2. Data Cleaning (Python)

Performed:

Removed duplicate records
Handled missing values
Corrected data types
Removed invalid bookings
Standardized column names
Fixed inconsistent values
3. Exploratory Data Analysis (EDA)

Performed analysis on:

Revenue trends
Booking trends
Occupancy
Cancellation rate
Average Daily Rate (ADR)
Revenue Per Available Room (RevPAR)
Customer ratings
Seasonal booking patterns

Used:

Bar Charts
Line Charts
Pie Charts
Histograms
Heatmaps
Correlation Matrix
4. SQL Analysis

Executed SQL queries to answer business questions such as:

Total Revenue
Revenue by City
Revenue by Hotel
Revenue by Room Category
Occupancy Rate
Cancellation Rate
Monthly Revenue
Booking Platform Performance
Top Performing Hotels
Average Customer Rating
5. Dashboard Development

Developed an interactive Power BI dashboard featuring:

KPI Cards
Revenue Trend Analysis
Occupancy Trend
Booking Analysis
Cancellation Analysis
ADR Analysis
RevPAR Analysis
Filters and Slicers
Drill-through Reports
📈 Key Performance Indicators (KPIs)
Total Revenue
Total Bookings
Successful Bookings
Occupancy Rate
Average Daily Rate (ADR)
RevPAR
Realisation %
Cancellation %
Average Rating
📊 Dashboard Features
Executive Summary
Revenue Dashboard
Booking Dashboard
Occupancy Dashboard
Hotel Performance Dashboard
City Performance Dashboard
Room Category Analysis
Booking Platform Analysis
Customer Rating Analysis
Monthly Trend Analysis
🔍 Business Insights

Some key insights generated from the dashboard include:

Identified cities generating the highest revenue.
Compared performance across hotel properties.
Measured occupancy trends throughout the year.
Evaluated booking platform effectiveness.
Identified room categories contributing the highest revenue.
Analyzed customer satisfaction through ratings.
Measured cancellation impact on revenue.
Tracked seasonal demand patterns.
📁 Repository Structure
Hotel-Revenue-Analysis/
│
├── data/
│   ├── bookings.csv
│   ├── hotels.csv
│   ├── rooms.csv
│   └── revenue.csv
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   └── eda.ipynb
│
├── sql/
│   └── hotel_analysis_queries.sql
│
├── powerbi/
│   └── Hotel_Revenue_Dashboard.pbix
│
├── images/
│   ├── dashboard.png
│   ├── revenue.png
│   └── occupancy.png
│
├── README.md
└── requirements.txt
📷 Dashboard Preview

Add screenshots of your Power BI dashboard here.

Suggested screenshots:

Executive Dashboard
Revenue Analysis
Occupancy Analysis
Booking Analysis
Hotel Performance
🚀 How to Run
Clone Repository
git clone https://github.com/yourusername/Hotel-Revenue-Analysis.git
Install Dependencies
pip install -r requirements.txt
Run Jupyter Notebook
jupyter notebook
Execute SQL Queries

Import the dataset into your SQL database (PostgreSQL/MySQL) and run the queries from the sql/ folder.

Open Power BI Dashboard

Open:

Hotel_Revenue_Dashboard.pbix

using Microsoft Power BI Desktop.

📌 Skills Demonstrated
Data Cleaning
Exploratory Data Analysis (EDA)
SQL Query Writing
Data Visualization
Business Intelligence
Power BI Dashboard Design
KPI Development
Business Analytics
Data Storytelling
Dashboard Reporting
📈 Future Improvements
Real-time dashboard using SQL Server.
Automated ETL pipeline.
Revenue forecasting using Machine Learning.
Customer segmentation analysis.
Dynamic report scheduling.
Integration with cloud databases (Azure/AWS).
🏆 Learning Outcomes

Through this project, I gained practical experience in:

Cleaning and preparing real-world datasets.
Performing SQL-based business analysis.
Building interactive Power BI dashboards.
Designing meaningful KPIs for hotel management.
Creating data-driven business reports.
Presenting insights through effective visualizations.
📬 Contact

Sahil Rajpure

LinkedIn: Add your LinkedIn profile
GitHub: https://github.com/yourusername
Email: your.email@example.com
