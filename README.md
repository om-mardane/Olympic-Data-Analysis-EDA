# 🏅 Olympic Dataset Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Olympic dataset using Python.  
The main objective is to analyze athlete performance, medal distribution, country participation, and historical Olympic trends.

This project demonstrates practical data cleaning, preprocessing, merging datasets, and visualization techniques using real-world sports data.

---

## 📂 Dataset Information

The dataset contains historical Olympic data with the following columns:

- ID – Unique athlete ID
- Name – Athlete name
- Sex – Gender of athlete
- Age – Athlete age
- Height – Height in cm
- Weight – Weight in kg
- Team – Country team name
- NOC – National Olympic Committee code
- Games – Olympic season and year
- Year – Year of Olympic event
- Season – Summer / Winter
- City – Host city
- Sport – Type of sport
- Event – Specific event
- Medal – Gold / Silver / Bronze / NaN

---

## 🎯 Objectives

- Perform data cleaning and preprocessing
- Handle missing values (especially Medal column)
- Analyze medal distribution by country
- Identify top-performing countries
- Perform gender-based participation analysis
- Study trends across Olympic years
- Visualize insights using graphs

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔎 Key Analysis Performed

1. Data Cleaning
   - Checked missing values
   - Filled missing medal values with "No Medal"
   - Removed unnecessary duplicates

2. Data Merging
   - Merged region dataset using:
     df = df.merge(regions, on="NOC", how="left")

3. Medal Analysis
   - Total medals by country
   - Gold medal distribution
   - Year-wise medal trends

4. Gender Analysis
   - Male vs Female participation
   - Gender-wise medal comparison

5. Sport Analysis
   - Most popular sports
   - Sports with highest medals

6. Visualization
   - Bar graphs
   - Line charts
   - Count plots
   - Heatmaps

---

## 📊 Sample Insights

- Some countries consistently dominate specific sports.
- Participation has increased significantly over time.
- Gender representation has improved in recent Olympic years.
- Medal distribution varies greatly between nations.
