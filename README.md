🦠 COVID-19 Data Analysis & Dashboard

📌 Project Overview

This project focuses on analyzing global COVID-19 data using Python. 
It includes data cleaning, exploratory data analysis (EDA), visualization, and an interactive dashboard using Plotly Dash.

The goal is to understand pandemic trends, identify high-risk countries, and extract meaningful insights from the dataset.

🎯 Objectives

Collect and preprocess COVID-19 dataset
Perform data cleaning and transformation
Analyze confirmed, deaths, recovered, and active cases
Visualize trends using charts and graphs
Build an interactive dashboard
Generate insights for decision-making

📂 Dataset

Source: Kaggle (country-wise latest COVID-19 data)
File used: country_wise_latest.csv
Features:
Country/Region
Confirmed Cases
Deaths
Recovered Cases
Active Cases (calculated)

🛠️ Technologies Used

.Python 🐍
.Pandas
.Matplotlib
.Seaborn
.Plotly Express
.Dash (for dashboard)

⚙️ Project Workflow

1️⃣ Import Libraries

.Load required Python libraries for data analysis and visualization

2️⃣ Data Collection

.Load dataset using Pandas
.Select required columns

3️⃣ Data Cleaning & Preprocessing

.Handle missing values
.Remove duplicates
.Convert data types
.Calculate Active cases

4️⃣ Descriptive Statistics

.Total Confirmed Cases
.Total Deaths
.Total Recovered
.Summary statistics using .describe()

5️⃣ COVID Trend Analysis

.Group data by date
.Analyze global trends over time

6️⃣ Country-Based Analysis

.Identify top affected countries
.Compare confirmed, deaths, and recovered cases

7️⃣ Data Visualization

📈 Line Chart
<img width="1382" height="544" alt="image" src="https://github.com/user-attachments/assets/dab61106-2de4-4884-add4-fa63c282c8d9" />

@Trend of confirmed cases over time

📊 Bar Chart
<img width="1383" height="542" alt="image" src="https://github.com/user-attachments/assets/d08937c5-3e5d-440d-83e3-2d8d3bd29aa4" />

@Top 10 countries by confirmed cases

🥧 Pie Chart
<img width="1383" height="547" alt="image" src="https://github.com/user-attachments/assets/365d26a2-6ee3-4ccb-85bf-d7309ff50063" />

@Distribution of confirmed, deaths, recovered

🔵 Scatter Plot
<img width="1383" height="540" alt="image" src="https://github.com/user-attachments/assets/8e13c057-29e0-4180-9eb9-a1cd50d05f27" />

@Relationship between confirmed vs deaths

🔥 Heatmap
<img width="1085" height="529" alt="image" src="https://github.com/user-attachments/assets/e5981809-288f-408d-b1b6-3399e1aa3875" />

@Correlation between variables

8️⃣ Dashboard (Plotly Dash)

.Interactive dropdown for country selection
.Dynamic graph updates
.Visual exploration of COVID data

9️⃣ Dashboard Insights

.Identify high-risk countries
.Analyze recovery trends
.Observe active case patterns

📊 Key Insights

.Countries like US, Brazil, and India had the highest confirmed cases
.COVID spread shows exponential growth patterns
.Recovery trends improved over time
.Death rates highlight severity in specific regions
.Active cases indicate current pandemic load


Name: Jency
Role: Data Analyst / Python Developer

📜 Conclusion

This project provides a comprehensive analysis of COVID-19 data using visualization and dashboard tools.
It helps in understanding pandemic trends and supports data-driven decision-making.
