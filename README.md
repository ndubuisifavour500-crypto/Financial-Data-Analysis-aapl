# Week 6: Advanced Python for Data Analysis
## AAPL Stock Market Analysis Project

**Intern:** Ndubuisi Favour Adaku  
**Organization:** AnalystLab Africa - Batch B  
**Program Period:** June - August 2026  
**Project Week:** Week 6 (June 30 - July 12, 2026)  
**Submission Date:** July 9, 2026

---

## 📋 Project Overview

This project demonstrates advanced Python techniques for financial data analysis using 5 years of Apple Inc. (AAPL) historical stock data. The analysis covers data transformation, time-series analysis, feature engineering, and professional data visualization.

**Key Achievement:** Analyzed 1,254 trading days to uncover a sustained 5-year uptrend with 115% total return, supported by volume confirmation and manageable volatility patterns.

---

## 📊 Deliverables Included

### 1. **Python Notebook** 
- File: `Week6_AAPL_Analysis.ipynb`
- Contains complete analysis pipeline
- Includes data loading, exploration, cleaning, transformation, and visualization
- Ready to run in Google Colab or Jupyter Notebook

### 2. **Analysis Report**
- **Format 1:** `Week6_AAPL_Analysis_Report.pdf` (PDF - Print Ready)
- **Format 2:** `Week6_AAPL_Analysis_Report.docx` (Word - Editable)
- 1-2 page comprehensive summary
- Includes dataset overview, methodology, findings, and recommendations

### 3. **Data Visualizations**
- Chart 1: AAPL Price Trend (5 Years)
- Chart 2: Moving Averages Analysis (7, 30, 90-day)
- Chart 3: Trading Volume Trend
- Chart 4: Daily Returns Distribution

### 4. **Social Media Content**
- LinkedIn post (professional tone)
- Twitter/X thread (engaging format)
- Both include #AnalystLabAfrica and relevant hashtags

---

## 🔍 Analysis Highlights

### Dataset
- **Source:** Yahoo Finance API (yfinance)
- **Time Period:** July 8, 2021 - July 8, 2026 (5 years)
- **Total Records:** 1,254 trading days
- **Data Quality:** No missing values, complete and validated

### Key Findings

#### Finding #1: Strong 5-Year Uptrend
- Price appreciation: $139.63 → $300+ (115% return)
- Consistent growth across all timeframes
- Clear moving average alignment confirms trend strength

#### Finding #2: Volume Confirms Trend
- Trading volume increases on up days
- Decreases during consolidation phases
- Indicates genuine institutional buying pressure

#### Finding #3: Manageable Volatility
- Daily volatility: ~2.2%
- Daily returns range: -8% to +8%
- Suitable for most investor risk profiles

#### Finding #4: Positive Return Distribution
- Slightly right-skewed distribution
- More positive days than negative
- Mean daily return consistently positive

---

## 🛠️ Technical Implementation

### Python Libraries Used
```python
import yfinance as yf          # Financial data retrieval
import pandas as pd             # Data manipulation
import numpy as np              # Numerical computing
import matplotlib.pyplot as plt  # Visualization
import seaborn as sns           # Statistical plotting
```

### Advanced Techniques Applied

#### Data Transformation
- ✓ Data cleaning & validation
- ✓ Missing value handling
- ✓ Data type conversion
- ✓ Duplicate removal
- ✓ Chronological sorting

#### Feature Engineering
- ✓ Daily price changes
- ✓ Daily return percentages
- ✓ Price range calculations
- ✓ Moving averages (7, 30, 90-day)
- ✓ Volatility measures
- ✓ Time-based features (year, month, quarter)

#### Time-Series Analysis
- ✓ Trend identification
- ✓ Rolling window calculations
- ✓ Distribution analysis
- ✓ Multi-timeframe comparison
- ✓ Volume confirmation patterns

---

## 📈 Visualizations Created

### Chart 1: AAPL Price Trend
Shows the overall price trajectory from July 2021 to July 2026, clearly depicting the sustained uptrend from approximately $140 to $300+.

### Chart 2: Moving Averages Analysis
Displays three moving average lines (7-day, 30-day, 90-day) alongside closing prices. Shows clear alignment indicating strong uptrend, with consistent buy signals at moving average touchdowns.

### Chart 3: Trading Volume Trend
Bar chart showing daily trading volume with color coding (green fo
