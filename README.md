

# 📈 Time Series Analysis on Stock Prices

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow?logo=pandas)
![Visualization](https://img.shields.io/badge/Visualization-Matplotlib-blue)
![Analysis](https://img.shields.io/badge/Analysis-Time%20Series-orange)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-orange?logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## Overview

This project performs time series analysis on stock price data to understand how prices change over time. It focuses on identifying trends, detecting patterns, and generating insights using visualization and basic forecasting techniques.

---

## Objective

* Analyze time-based trends
* Detect seasonality patterns
* Apply basic forecasting
* Generate time-based insights

---

## Dataset

**Stock Price Dataset**

The dataset contains:

* `date` → Time component of the data
* `last_value` → Stock price (used for analysis)

---

## Tasks Performed

### 1. Data Preprocessing

* Converted `date` column to datetime format
* Sorted dataset chronologically
* Set date as index for time series analysis
* Removed missing values

---

### 2. Trend Analysis

* Plotted stock price (`last_value`) over time
* Identified overall upward/downward movement

---

### 3. Seasonality Detection

* Resampled data on a monthly basis
* Calculated average price per month
* Observed repeating patterns and fluctuations

---

### 4. Moving Average

* Applied 30-day moving average
* Smoothed short-term fluctuations
* Highlighted long-term trends

---

### 5. Forecasting (Optional)

* Used shifting method to estimate future values
* Compared actual vs predicted values

---

## Results

* Clear trend observed in stock prices over time
* Monthly aggregation revealed periodic patterns
* Moving average reduced noise and improved trend visibility
* Forecast provided approximate future values

---

## Output

* Time-based trend visualization
* Seasonality insights
* Smoothed trend using moving average
* Basic forecast of future stock prices

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab

---

## Run on Google Colab

1. Open Google Colab
2. Upload the dataset (`Stock Price.csv`)
3. Run the notebook step by step

Add your notebook link here:

```id="ts7final"
https://colab.research.google.com/drive/YOUR_NOTEBOOK_LINK
```

---

## Project Structure

```id="ts7finalstruct"
Time-Series-Stock-Analysis
│
├── README.md
├── analysis.ipynb
└── dataset/
    └── Stock Price.csv
```

---

## Author

**Sakshi Patel**

