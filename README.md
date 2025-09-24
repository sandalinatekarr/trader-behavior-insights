# Trader Performance Insights Based on Bitcoin Market Sentiment Analysis  

## 📌 Overview  
This project analyzes the relationship between **trader performance** and **Bitcoin market sentiment** by using two primary datasets:  

- **Bitcoin Market Sentiment Dataset (Fear/Greed Index)**  
- **Historical Trader Data from Hyperliquid**  

The goal is to uncover hidden patterns and provide actionable insights to help design smarter trading strategies in the Web3 space.  

---

## 📑 Datasets  
- **Bitcoin Market Sentiment Dataset** → Contains daily sentiment classification (*Fear/Greed*) indexed by date.  
- **Historical Trader Data** → Detailed trade-level data including account info, symbol, execution price, size, side (buy/sell), timestamps, closed profit & loss (PnL), leverage, and more.  

📂 Dataset Links (provided in assignment):  
- [Historical Trader Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)  
- [Fear & Greed Index](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)  

---

## 🔄 Analysis Workflow  
The Jupyter notebook **`01_data_cleaning.ipynb`** contains the following key steps:  

1. **Load and Clean Data** → Read datasets and preprocess for analysis.  
2. **Merge Datasets** → Join sentiment information with trade records by date.  
3. **Summary Statistics** → Overview of trade volumes and performance by sentiment.  
4. **PnL and Win Rate Analysis** → Compare average profit and win rates across sentiment categories.  
5. **Trade Size Analysis** → Distribution of trade sizes in different market moods.  
6. **Symbol and Account Level Insights** → Performance breakdown by coins and top traders.  
7. **Correlation & Time-Based Analysis** → Explore relationships and trends over time.  
8. **Trade Side (Buy vs Sell) Impact** → How trade direction performs under various sentiments.  
9. **Visualizations** → Charts to illustrate findings at different granularities.  

---

## 📊 Key Findings  
- Traders generally perform **better during extreme greed conditions**.  
- Performance and win rate **drop during periods of fear**, indicating higher risk and panic-driven behavior.  
- Certain coins and traders consistently outperform under specific sentiment conditions.  
- Trade size and leverage vary meaningfully across sentiment classifications.  

---
