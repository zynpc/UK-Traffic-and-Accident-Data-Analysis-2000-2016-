# UK Traffic and Accident Data Analysis (2000–2016)

This project analyzes historical traffic and accident data in the United Kingdom between the years 2000 and 2016. It consists of data cleaning, exploratory data analysis (EDA), and machine learning models to extract insights and predict future traffic behavior.

## Objective

This project seeks to provide a comprehensive analysis of traffic flow and accident data in the United Kingdom over the years 2000 to 2016. The main goals include:

- Exploring traffic volume trends and identifying patterns by vehicle types, regions, and road categories.
- Analyzing accident distribution in terms of geography and timing to better understand risk factors.
- Developing predictive models to estimate traffic density levels and forecast vehicle counts on roads.

By combining statistical analysis with machine learning techniques, the project aims to deliver actionable insights for policymakers, urban planners, and traffic safety authorities to optimize infrastructure and reduce accidents.

## Datasets Used
Two different datasets were used:

1. **ukTrafficAADF.csv:** Includes yearly traffic volume data for various vehicle types across different regions and road categories.
2. **accidents_2012_to_2014.csv:** Contains records of traffic accidents, including date, time, location, and severity.

## Exploratory Data Analysis

### Traffic Dataset Analyses:
- Total Number of Motor Vehicles by Year (Trend Analysis)
- Average Traffic Volume by Region
- Vehicle Count Distribution by Road Category
- Most Common Estimation Methods Used
- Top 10 Count Points with Highest Total Vehicle Count
- Time Series Trend of Vehicle Counts (2000–2016) with Vehicle Type Breakdown

### Road Accidents Dataset Analyses:
- Total Number of Accidents by Year and Trend
- Distribution of Accidents by Region (Local Authority)
- Accident Time Analysis (Hourly, Daily, Seasonal Distributions)

## Machine Learning Models
Two machine learning models were implemented:

1. **Traffic Density Estimation:** A classification model to predict traffic density levels as *Low*, *Medium*, or *High*.
2. **Linear Regression Model:** Predicts total vehicle count using selected features. Model performance is evaluated using RMSE and R² metrics.

## Technologies Used
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Machine Learning (Classification & Regression)

---

By combining traffic data with accident records and predictive modeling, this project provides meaningful insights into transportation trends and helps inform future urban planning and safety measures.
