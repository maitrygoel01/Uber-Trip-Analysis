# 🚖 Uber Trip Analysis Dashboard

## 📌 Project Overview

The **Uber Trip Analysis Dashboard** is a comprehensive Power BI solution designed to analyze ride bookings, trip performance, customer travel behavior, vehicle utilization, payment preferences, and operational efficiency.

The dashboard transforms raw trip-level data into actionable insights, enabling transportation businesses and operations teams to monitor booking trends, identify peak demand periods, optimize fleet utilization, and improve overall service performance.

The solution consists of three interactive reporting layers:

- Executive Overview Dashboard
- Time-Based Trip Analysis
- Transaction-Level Details Dashboard

---

## 🎯 Business Problem

Ride-hailing platforms generate thousands of trips daily, making it challenging to monitor operational performance and answer critical business questions such as:

- How many trips were completed?
- What revenue was generated?
- Which vehicle types are most popular?
- What are the busiest booking hours?
- Which locations generate the highest demand?
- What payment methods do customers prefer?
- How does trip demand vary by day and time?
- What are the most frequent pickup and dropoff locations?

The objective of this dashboard is to provide a centralized analytics platform for monitoring booking activity, customer travel patterns, fleet performance, and operational KPIs.

---

# 📊 Executive KPIs

| KPI | Value |
|------|--------|
| Total Bookings | 103.7K |
| Total Booking Value | $1.6M |
| Average Booking Value | $15.0 |
| Total Trip Distance | 349K Miles |
| Average Trip Distance | 3 Miles |
| Average Trip Time | 16 Minutes |

---

# 🔷 1. Executive Overview Analysis

The Overview Dashboard provides a high-level summary of trip performance, revenue generation, customer preferences, and location insights.

---

## Business Questions Answered

- How many bookings were completed?
- What revenue was generated?
- Which payment methods are preferred?
- What percentage of trips occur during day versus night?
- Which locations generate the highest demand?
- Which vehicle categories perform best?

---

## Booking Performance Analysis

Tracks:

- Total Bookings
- Revenue Generated
- Average Booking Value
- Total Distance Covered

### Key Insight

The platform processed over **103,000 trips**, generating approximately **$1.6M in booking revenue**.

---

## Payment Type Analysis

Payment methods analyzed include:

- Uber Pay
- Cash
- Amazon Pay
- Google Pay

### Business Value

Understanding customer payment preferences helps improve payment infrastructure and user experience.

---

## Day vs Night Trip Analysis

Trips are categorized into:

- Day Trips
- Night Trips

### Key Insight

Day trips contribute the majority of bookings, highlighting commuter-driven demand patterns.

---

## Location Analysis

The dashboard identifies:

### Most Frequent Pickup Point

**Penn Station / Madison Square West**

### Most Frequent Dropoff Point

**Upper East Side North**

### Longest Trip

**Lower East Side → Crown Heights North (144.1 Miles)**

---

## Vehicle Performance Analysis

Vehicle categories analyzed:

- UberX
- UberXL
- Uber Comfort
- Uber Black
- Uber Green

Metrics include:

- Total Bookings
- Revenue Generated
- Average Booking Value
- Distance Traveled

### Business Value

- Fleet optimization
- Vehicle allocation planning
- Revenue contribution analysis

---

# 🔷 2. Time-Based Trip Analysis

The Time Analysis Dashboard focuses on identifying booking patterns across hours, days, and time periods.

---

## Business Questions Answered

- When is booking demand highest?
- Which days generate the most bookings?
- What hours require additional vehicle availability?
- How does demand vary throughout the week?

---

## Booking Trend by Pickup Time

Analyzes trip demand throughout the day.

### Key Insight

Booking demand increases significantly during:

- Morning commute hours
- Afternoon peak periods
- Evening travel windows

---

## Day-Wise Booking Analysis

Compares total bookings across weekdays.

### Observations

| Day | Bookings |
|------|-----------|
| Monday | 14.7K |
| Tuesday | 15.1K |
| Wednesday | 15.7K |
| Thursday | 11.2K |
| Friday | 9.3K |
| Saturday | 18.7K |
| Sunday | 19.2K |

### Key Insight

Weekend demand significantly exceeds weekday demand, indicating strong leisure travel activity.

---

## Hour & Day Heatmap Analysis

The heatmap visualizes booking density across:

- Hours of Day
- Days of Week

### Insights Generated

- Peak demand periods
- Low utilization windows
- Workforce planning opportunities
- Surge pricing opportunities

---

## Business Value

- Driver scheduling optimization
- Fleet allocation planning
- Peak-hour resource management
- Demand forecasting

---

# 🔷 3. Location Intelligence Analysis

Location analysis helps identify operational hotspots and travel patterns.

---

## Metrics Evaluated

- Frequent Pickup Locations
- Frequent Dropoff Locations
- Trip Density by Location
- Preferred Vehicle by Location

---

## Top Booking Locations

The dashboard highlights:

- Most active pickup zones
- High-demand neighborhoods
- Revenue-generating travel corridors

---

## Preferred Vehicle Analysis

Identifies the most commonly selected vehicle type by location.

### Key Insight

**UberX** dominates ride demand across most pickup locations.

---

## Business Value

- Service expansion planning
- Fleet distribution optimization
- Location-based promotions
- Demand hotspot identification

---

# 🔷 4. Vehicle Performance Analysis

The Vehicle Performance section evaluates utilization and profitability by vehicle category.

---

## Vehicle Types Analyzed

- UberX
- UberXL
- Uber Comfort
- Uber Black
- Uber Green

---

## Metrics Evaluated

- Booking Count
- Revenue Contribution
- Average Booking Value
- Distance Traveled

---

## Key Insights

- UberX generates the highest booking volume.
- Premium vehicles contribute higher-value bookings.
- Vehicle utilization varies significantly by location.

---

## Business Value

- Fleet optimization
- Revenue maximization
- Driver allocation planning
- Service portfolio management

---

# 🔷 5. Transaction Details & Drill-Through Analysis

The Details Dashboard provides transaction-level visibility into individual trips.

This page serves as the operational reporting layer of the solution and enables users to validate KPI calculations and investigate specific bookings.

---

## Business Questions Answered

- Which vehicle was used?
- What payment method was selected?
- What was the trip distance?
- What was the booking value?
- Where did the trip start and end?
- How many passengers traveled?

---

## Available Transaction Attributes

| Field |
|---------|
| Trip ID |
| Pickup Date |
| Vehicle Type |
| Payment Type |
| Passenger Count |
| Trip Distance |
| Booking Value |
| Pickup Location |
| Dropoff Location |
| Total Bookings |

---

## Transaction Summary

| Metric | Value |
|---------|--------|
| Total Trips | 103,728 |
| Total Revenue | $1.54M |
| Total Distance | 348,933 Miles |

---

## Interactive Features

Users can:

- Search specific trips
- Analyze trip-level performance
- Validate summary metrics
- Review payment behavior
- Investigate location activity
- Export detailed data

---

## Business Value

The Details Dashboard supports:

- Transaction auditing
- Revenue verification
- Customer travel analysis
- Operational investigations
- Data transparency

---

# 📈 Key Business Insights

## Revenue Insights

- Generated approximately **$1.6M** in booking value.
- Average booking value remained stable at **$15**.

---

## Demand Insights

- More than **103K bookings** were completed.
- Weekend demand exceeds weekday demand.
- Peak activity occurs during commuting and evening hours.

---

## Fleet Insights

- UberX remains the most utilized vehicle category.
- Premium vehicle categories contribute higher-value trips.

---

## Location Insights

- Penn Station/Madison Square West is the most frequent pickup location.
- Upper East Side North is the most frequent dropoff destination.
- Geographic hotspots reveal strong concentration of demand.

---

# 🛠️ Technical Implementation

## Data Modeling

A Star Schema data model was implemented to improve reporting performance and maintainability.


<img width="1217" height="791" alt="image" src="https://github.com/user-attachments/assets/ecec24b2-96d3-49ec-ad26-01c449430470" />


### Fact Tables

- Fact Trips
- Fact Bookings
- Fact Revenue

### Dimension Tables

- Dim Date
- Dim Vehicle
- Dim Location
- Dim Payment Type

---

## Power Query Transformations

Data preparation included:

- Data Cleaning
- Null Value Handling
- Data Type Standardization
- Data Validation
- Relationship Creation
- Derived Columns

---

## DAX Measures

```DAX
Total Bookings

Total Booking Value

Average Booking Value

Total Trip Distance

Average Trip Distance

Average Trip Time

Day Trips

Night Trips

Booking Growth %

Revenue by Vehicle

Revenue by Payment Type

Top Pickup Location

Top Dropoff Location
```



# 📷 Dashboard Screenshots

## Executive Overview Dashboard

<img width="1297" height="732" alt="image" src="https://github.com/user-attachments/assets/8c7f9abc-20b1-4e5d-85fc-a3854d54e86f" />

---

## Time Analysis Dashboard

<img width="1308" height="735" alt="image" src="https://github.com/user-attachments/assets/8a710bd6-ed9a-4934-a754-1bcd7bac591d" />

---

## Transaction Details Dashboard

<img width="1296" height="740" alt="image" src="https://github.com/user-attachments/assets/ed79fa53-58ad-4294-b148-2b32cecfadd8" />

---

# 📂 Project Structure

```text
Uber-Trip-Analysis-Dashboard/
│
├── Dataset/
│   └── Uber_Trip_Data.xlsx
│
├── Dashboard/
│   └── Uber_Trip_Analysis.pbix
│
├── Images/
│   ├── uber-overview.png
│   ├── uber-time-analysis.png
│   └── uber-details.png
│
└── README.md
```

# 📌 Conclusion

The **Uber Trip Analysis Dashboard** provides a complete transportation analytics solution by combining booking performance, revenue tracking, fleet utilization, location intelligence, time-based demand analysis, and transaction-level reporting into a single interactive Power BI experience.

The dashboard enables operations teams, business stakeholders, and decision-makers to monitor performance, optimize resource allocation, improve customer service, and make data-driven decisions using actionable trip analytics.

---

### ⭐ Project Summary

> An interactive Power BI dashboard that analyzes Uber trip bookings, revenue performance, fleet utilization, location intelligence, time-based demand patterns, and transaction-level activity to support data-driven transportation and operational decision-making.
