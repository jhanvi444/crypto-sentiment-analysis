# Crypto Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using two datasets:

- Bitcoin Fear & Greed Index
- Historical Hyperliquid Trading Data

The objective is to explore how market sentiment influences trading performance and identify patterns that can help support smarter trading strategies.

---

## Project Structure

```
crypto-sentiment-analysis/
│
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── notebook.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

1. Imported and explored both datasets.
2. Cleaned and formatted the data.
3. Converted timestamp columns into a common date format.
4. Merged trading data with the Fear & Greed Index.
5. Performed Exploratory Data Analysis (EDA).
6. Visualized trader performance under different market sentiments.
7. Generated business insights and conclusions.

---

## Key Analyses

- Number of trades by market sentiment
- Average Closed PnL by sentiment
- Total Closed PnL by sentiment
- Profit vs Loss distribution
- BUY vs SELL performance comparison

---

## Key Findings

- Fear periods recorded the highest trading activity.
- Extreme Greed produced the highest average profit per trade.
- Fear generated the highest overall profit due to higher trading volume.
- More trades resulted in losses than profits, highlighting the importance of effective risk management.
- Market sentiment appears to influence trader behavior and profitability.

---

## Conclusion

The analysis demonstrates that market sentiment has a measurable relationship with trading performance. While Fear periods attracted the greatest trading activity, Extreme Greed resulted in the highest average profit per trade. These findings suggest that sentiment indicators can provide valuable context for understanding market behavior and improving trading decisions when combined with disciplined risk management.

---

## Author

**Jhanvi Atri**
