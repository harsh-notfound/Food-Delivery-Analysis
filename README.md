🍔 Food Delivery Analysis Dashboard (Egypt)

An interactive Power BI dashboard that analyzes food delivery operations across Egyptian restaurants. It brings revenue, delivery performance, driver availability, menu performance, and payment behavior into one view, filterable by city and traffic level.

<img width="1276" height="707" alt="Screenshot 2026-09-23 233224" src="https://github.com/user-attachments/assets/ae3b4922-b7d6-48a4-a294-ba1f06e13506" />

📌 Project Overview

Food delivery businesses need to know when demand peaks, how fast orders are delivered, and whether enough drivers are available. This project answers those questions by turning raw order data into a clean, interactive report.

🎯 Objectives
Measure overall revenue and average delivery time
Compare revenue and driver availability across the day
Evaluate delivery time by vehicle type
Identify top-selling menu items
Understand the split between payment methods
Let users drill down by city and traffic level
📊 Dashboard Contents
Visual	What it shows
KPI cards	Total Revenue (26.89M) and Average Delivery Time (37.52 min)
Revenue & Driver Availability by Time Frame	Combo chart: revenue (columns) vs. driver availability (line) across six 4-hour windows
Delivery Time & Driver Availability by Vehicle	Average delivery duration and driver count for Car, Bicycle, and Motorbike
Revenue by Item	Total revenue for each menu item (Shawarma, Pizza, Fried Chicken, Koshary, Pasta, Burger, Salad, Sandwich, Sushi)
Revenue by Payment Method	Share of Cash, Wallet, and Credit Card
Slicers	Filter by City and Traffic Level (High / Medium / Low)

Cities covered: Alexandria, Assiut, Cairo, Giza, Mansoura, Tanta, Zagazig

🔍 Key Observations
Revenue is spread fairly evenly across the six time frames, while driver availability declines from late night through the evening.
Average delivery time is about 37.5 minutes, with only small differences between vehicle types.
Payments are split almost equally across Cash, Wallet, and Credit Card (about 33% each).
Shawarma is the top-earning item, though revenue across items is close.

🛠️ Tools & Techniques
Power BI Desktop: data modeling, visuals, slicers, theming
DAX: calculated columns and measures
Data cleaning: Pandas(python)
