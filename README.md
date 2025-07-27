# MarketPulse-Stock-Sentiment-Price-Movement-Predictor
## 🧠 DailyStockPredictor: Demand Forecasting for E-Commerce

Built a time-series forecasting pipeline using historical SKU-level sales data to predict future inventory needs and optimize restocking decisions.

### 🔧 Key Features
- Developed demand forecasting pipeline using **XGBoost** for daily SKU-level inventory prediction.
- Engineered time-based features (week, month, lag, event spikes); achieved **10% RMSE**.
- Generated optimal restocking thresholds using **smoothed demand curves** to reduce stockouts and enable proactive planning.

---

## 📈 MarketPulse: Stock Sentiment & Price Movement Predictor

Analyzed financial news sentiment and correlated it with stock price movements to uncover predictive relationships.

### 🔧 Key Features
- Collected stock headlines using **NewsAPI** and historical prices via **Yahoo Finance API**.
- Built sentiment classifier using **TF-IDF + Logistic Regression** to tag headlines as positive/negative.
- Correlated daily sentiment scores with stock movement labels (up/down) to analyze market trends.
- Achieved **78% accuracy** in binary movement classification; visualized sentiment trends using **Seaborn**.

---

### 🚀 Tools & Technologies
`Python` `Pandas` `Scikit-learn` `XGBoost` `Matplotlib` `Seaborn` `TF-IDF` `Yahoo Finance API` `NewsAPI`
