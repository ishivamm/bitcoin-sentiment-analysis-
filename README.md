# Bitcoin Market Sentiment vs Trader Performance Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using Hyperliquid historical trading data along with the Fear & Greed Index dataset.

The objective is to uncover how different market emotions such as Fear, Greed, Extreme Fear, and Extreme Greed influence trader profitability, trading behavior, and overall market activity.

The analysis combines:
- Exploratory Data Analysis (EDA)
- Behavioral trading analysis
- Market sentiment analysis
- Machine Learning prediction models

---

# Problem Statement

Financial markets are heavily influenced by investor psychology and sentiment.  
This project investigates whether market sentiment can provide meaningful insights into trader performance and profitability.

The key goals are:

- Analyze trader profitability under different sentiment conditions
- Understand how trading behavior changes across market phases
- Identify profitable market conditions
- Build predictive models for trade profitability

---

# Datasets Used

## 1. Bitcoin Fear & Greed Index Dataset

Contains:
- Date
- Sentiment classification
- Sentiment score/value

Sentiment categories:
- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

---

## 2. Hyperliquid Historical Trader Dataset

Contains:
- Account
- Coin
- Execution Price
- Size Tokens
- Size USD
- Side
- Direction
- Closed PnL
- Fee
- Timestamp
- Order information

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Project Workflow

## 1. Data Cleaning
- Handled missing values
- Converted timestamps into datetime format
- Standardized columns

## 2. Feature Engineering
Created additional features such as:
- Sentiment score
- Profit/Loss indicator
- Market phase
- Trading hour

## 3. Exploratory Data Analysis
Performed:
- Profitability analysis
- Trading volume analysis
- Coin-wise analysis
- Trader behavior analysis
- Time-based analysis

## 4. Visualization
Created visualizations including:
- Bar charts
- Boxplots
- Heatmaps
- Correlation analysis
- Profitability comparisons

## 5. Machine Learning
Built a Random Forest Classification model to predict whether a trade will be profitable.

Features used:
- Sentiment score
- Size USD
- Execution Price
- Fee

---

# Key Insights

## Market Sentiment Impacts Profitability
Fear and Extreme Greed periods showed higher trading profitability compared to Neutral markets.

## Emotional Markets Increase Activity
Trading volume and market participation increased significantly during emotionally volatile market conditions.

## Trade Timing Matters
Certain trading hours consistently showed stronger average profitability.

## Coin Performance Varies
Some cryptocurrencies generated significantly higher profits than others.

## Sentiment Helps Predict Trade Success
Market sentiment proved to be a useful feature in predicting profitable trades.

---

# Machine Learning Results

A Random Forest model was trained to classify profitable vs non-profitable trades.

### Model Objective
Predict:
- Profitable Trade (1)
- Non-Profitable Trade (0)

### Features Used
- Sentiment Score
- Trade Size (USD)
- Execution Price
- Trading Fee

### Evaluation
The model was evaluated using:
- Accuracy Score
- Feature Importance Analysis

---

# Visualizations Included

- Trade Count by Sentiment
- Average PnL by Sentiment
- Coin-wise Profitability
- Win Rate Analysis
- Top Traders Analysis
- Correlation Heatmap
- Hourly Profitability Trends

---

# Repository Structure

```bash
bitcoin-sentiment-analysis/
│
├── Analysis_notebook.ipynb
├── historical_data.csv
├── fear_greed_index.csv
├── README.md
├── requirements.txt
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/ishivamm/bitcoin-sentiment-analysis.git
```

Move into the project folder:

```bash
cd bitcoin-sentiment-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
Analysis_notebook.ipynb
```

---

# Future Improvements

Potential enhancements include:
- Real-time sentiment tracking
- Advanced ML models
- Strategy backtesting
- Risk-adjusted return metrics
- Trader clustering analysis
- Deep learning models for prediction

---

# Conclusion

This project demonstrates that market sentiment strongly influences trader behavior and profitability.

The findings suggest that:
- Emotional market phases create larger trading opportunities
- Sentiment-aware strategies can improve decision making
- Behavioral analysis can help design smarter trading systems

This project combines data analysis, visualization, feature engineering, and machine learning to derive actionable insights from financial trading data.

---

# Author

## Shivam Maurya
