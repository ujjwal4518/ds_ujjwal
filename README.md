# 📊 Trader Behavior Insights vs Market Sentiment

**👤 Candidate**: Ujjwal Dwivedi  
**📅 Submission Date**: July 27, 2025  
**💼 Role**: Junior Data Scientist – Trader Behavior Insights  
**📩 Submission To**: saami@bajarangs.com, nagasai@bajarangs.com, chetan@bajarangs.com (cc: sonika@primetrade.ai)

---

---

## 📌 Objective

Analyze how **trader behavior** (profit, risk, volume, leverage) aligns or diverges from **market sentiment** (Fear vs Greed).  
Goal is to uncover insights that can drive smarter, sentiment-aware trading strategies in crypto.

---

## 📂 Datasets Used

1. **Bitcoin Market Sentiment Dataset**

   - Columns: `timestamp`, `value`, `classification` (Fear/Greed), `date`

2. **Historical Trader Data from Hyperliquid**
   - Columns: `Account`, `Coin`, `Size USD`, `Closed PnL`, `Leverage`, etc.

---

## 🧠 Key Insights

- **PnL increases** during Greed phases; higher loss outliers during Fear.
- **Trade sizes** (USD) increase during Greed sentiment.
- **Leverage** (where available) tends to rise with Greed.

📈 Visuals saved in the `outputs/` directory and embedded in the report.


---

## 📄 Report Summary

See [ds_report.pdf](./ds_report.pdf) for full EDA, visualizations, and strategic insights.  
Charts included:

- Closed PnL vs Sentiment
- Trade Volume vs Sentiment
- Leverage vs Sentiment

---
