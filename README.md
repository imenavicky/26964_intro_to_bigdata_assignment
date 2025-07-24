# 🚖 Uber Fares Dataset Analysis (Power BI Project)

## 📌 Project Overview

This project analyzes the Uber Fares dataset using Python (for data preparation) and Power BI (for data visualization). The goal is to uncover insights into ride patterns, fare behavior, and operational trends over time.

> 🔍 **Course**: INSY 8413 - Introduction to Big Data Analytics  
> 👨‍🏫 **Instructor**: Eric Maniraguha  
> 🗓️ **Assignment Date**:24th July 2025

> name: **IMENA VICKY** ID:**26964**

---

## 📁 Dataset Description

- **Source**: [Kaggle - Uber Fares Dataset](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)
- **File**: `UberDataset.xlsx` → cleaned and saved as `enhanced_uber_data.csv`
- **Key Features**:
  - `fare_amount`
  - `pickup_datetime`
  - `pickup_latitude`, `pickup_longitude`
  - `dropoff_latitude`, `dropoff_longitude`
  - `passenger_count`
  - `trip_distance` (engineered)
  - `hour`, `weekday`, `month`, `peak_time` (engineered)

---

## 🧪 Methodology

### 1. **Data Cleaning & Preparation** (Python):
- Removed missing or invalid entries
- Created `trip_distance` using the Haversine formula
- Extracted time-based features: `hour`, `day`, `month`, `weekday`
- Classified `peak_time` (peak vs off-peak)
- Saved as `enhanced_uber_data.csv` for use in Power BI

### 2. **Data Analysis & Visualization** (Power BI):
- Imported the enhanced CSV
- Built visualizations and dashboard

---

## 📊 Key Visualizations in Power BI

| Visualization                          | Description                                  |
|----------------------------------------|----------------------------------------------|
| **Fare vs Trip Distance (Scatter)**    | Shows fare relationship with distance        |
| **Average Fare by Hour (Column)**      | Highlights peak fare times                   |
| **Rides per Weekday (Bar Chart)**      | Weekday distribution of rides                |
| **Monthly Trends (Line Chart)**        | Monthly ride volume or revenue               |
| **Pickup Map (Geo Chart)**             | Spatial analysis of pickup locations         |
    
---

## 💡 Insights & Discoveries

- Fare increases steadily with trip distance.
- Higher average fares occur during early mornings and evenings (rush hours).
- Most rides happen on weekdays.
- Fare distribution is right-skewed, with many low-fare rides and few high-fare ones.
- Maps show urban clusters as high-frequency pickup areas.

---

## 📂 Files Included

| File Name                | Description                              |
|--------------------------|------------------------------------------|
| `enhanced_uber_data.csv` | Cleaned and feature-engineered dataset   |
| `uber_dashboard.pbix`    | Power BI dashboard file                  |
| `screenshots/`           | Images showing cleaning + dashboard steps|
| `README.md`              | This project summary                     |

---

## ✅ screenshots i used

**1.UBER ANALYSIS IN POWER BI**
<img width="955" height="376" alt="uber analysis" src="https://github.com/user-attachments/assets/1f383498-a706-422b-85ca-adc6c8f4b0f1" />


**2.Load Dataset in Python**
<img width="960" height="510" alt="load dataset in python" src="https://github.com/user-attachments/assets/6dc3a585-039f-43f2-8c57-4b84cdaebefe" />
**3.Check dimensions and structure:**
<img width="960" height="424" alt="structure" src="https://github.com/user-attachments/assets/95008829-b806-4b0e-baed-7dd9b5b1b43f" />
<img width="958" height="424" alt="dimensions" src="https://github.com/user-attachments/assets/0538f03f-429b-49d9-a13d-8b4726e84948" />
**4.handle missing values and export cleaning data**
<img width="894" height="148" alt="handle missing values and export cleaning data" src="https://github.com/user-attachments/assets/18b4d337-5ce6-4676-b870-246f6bccdd92" />
**5.DESCRIPTIVE STATISTICS**

<img width="960" height="423" alt="descriptive statitistics" src="https://github.com/user-attachments/assets/d933abce-29b8-42d0-ba0e-e87462469f06" />


**Summary of Main Findings**

- Uber rides follow clear temporal and spatial patterns
- Ride volume and fare pricing are influenced by peak/off-peak times
- Urban locations show ride hotspots
- Feature engineering added meaningful insights to original dataset
  
**Recommendations: Data-Driven Suggestions**

- 🚦 Use dynamic pricing in known peak hours
- 🚗 Allocate more vehicles in pickup hotspots
- 💸 Offer promotions during off-peak to balance traffic
- 📱 Enhance app with live pricing/wait alerts for users


## 📌 Conclusion

This project demonstrates the process of transforming raw data into interactive insights using Python and Power BI. The insights can help ride-hailing services optimize pricing and understand customer patterns.

