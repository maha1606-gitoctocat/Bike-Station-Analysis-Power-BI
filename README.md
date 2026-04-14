Bike Sharing System Analysis Dashboard (Power BI)
📌 Project Overview

This project focuses on analyzing a Bike Sharing System dataset using Power BI to uncover insights related to bike availability, station utilization, and operational efficiency.

The dashboard provides an interactive and data-driven approach to monitor system performance and support better decision-making for urban mobility.

🎯 Objectives

Monitor bike availability and station capacity

Analyze station utilization efficiency

Identify high-performing and underperforming stations

Compare city-wise (contract-wise) performance

Track time-based trends in bike availability

Support operational decisions like bike redistribution

📊 Dashboard Features

🔹 KPI Metrics

Total Bikes

Total Stations

Active Stations

Total Available Bikes

Average Bikes per Day

Bike Utilization %

🔹 Visualizations Used

📊 Bar Chart → Top stations by available bikes

🍩 Donut Chart → Banking vs Non-banking stations

📈 Line Chart → Monthly bike availability trend

📉 Clustered Bar Chart → City-wise comparison

📋 Table → Station-level detailed insights

🎯 Gauge Chart → Utilization percentage

Data Model

The project follows a Star Schema:

🔸 Fact Table

Bike_Stations

Contains measures like:

Available Bikes
Bike Stands

Available Bike Stands

Last Update

🔸 Dimension Tables

Dim_Station → Station details (Name, Location)

Dim_Contract → City-level grouping

Dim_Date → Time analysis

Dim_Status → Station status (Open/Closed)

Dim_Banking → Payment availability

Dim_Bonus → Bonus feature

👉 All relationships are One-to-Many (1:*) with single-direction filtering

Key Insights

🚲 The system operates with ~6K bikes across ~1K stations

📍 913 stations are active, indicating strong network coverage

⚖️ Moderate utilization rate (~60–70%), suggesting optimization opportunities

🚨 Presence of empty and full stations indicates uneven bike distribution

🌆 Major cities (e.g., Lyon, Brussels) show higher demand and capacity

💳 Majority of stations are non-banking, highlighting improvement scope

📅 Stable trends indicate consistent demand over time

💡 Business Recommendations

🔄 Implement bike redistribution strategies

📍 Increase bikes in high-demand stations

📉 Optimize underutilized stations

💳 Expand banking-enabled stations

📊 Use real-time monitoring for better operations

🛠️ Tools & Technologies

Power BI

DAX (Data Analysis Expressions)

Power Query (Data Transformation)

Excel (Data Source)
