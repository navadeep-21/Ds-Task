# Ds-Task
#  Bitcoin Market Sentiment vs Trader Performance Analysis

##  Project Overview

This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **trader performance** using real-world trading data from Hyperliquid.

The goal is to understand how market emotions influence trading behavior, profitability, and risk-taking patterns.

---

##  Datasets Used

* **Fear & Greed Index Dataset**

  * Columns: `date`, `classification` (Fear/Greed)
* **Historical Trading Data**

  * Includes: Account, Trade Size, Side (Buy/Sell), Direction, Closed PnL, Timestamp, etc.

---

##  Key Steps Performed

* Data cleaning and preprocessing
* Fixed timestamp inconsistencies (used `Timestamp IST`)
* Feature engineering (date extraction & merging datasets)
* Exploratory Data Analysis (EDA) with visualizations
* Trader behavior and performance analysis

---

##  Key Insights

* Traders tend to achieve higher profits during **Greed** market conditions
* **Fear phases** are associated with increased losses due to cautious or panic-driven trading
* Trading behavior changes with sentiment:

  * More **Buy trades during Greed**
  * More **Sell trades during Fear**
* Larger trade sizes lead to higher profit/loss volatility (higher risk)
* A small group of traders consistently outperform others

---

##  Conclusion

Market sentiment plays a crucial role in influencing trading decisions and outcomes.
Understanding Fear and Greed patterns can help traders:

* Improve timing of trades
* Manage risk effectively
* Build smarter, data-driven trading strategies

---

##  Tech Stack

* Python 
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn (optional modeling)

---

##  Future Improvements

* Build predictive models for profit estimation
* Incorporate more market indicators (price, volume, volatility)
* Real-time sentiment-based trading strategy

---

##  Author

**Navadeep Tallam**
Aspiring Data Analyst | AI & ML Enthusiast
