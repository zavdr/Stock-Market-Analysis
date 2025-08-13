# 📈 s&p 500 predictor

a simple python project that downloads, cleans, and analyzes s&p 500 index data, then builds a basic model to predict whether the market will go up or down the next day.

---

## 🛠 features
- fetches historical s&p 500 data using `yfinance`
- cleans and preprocesses data with `pandas`
- creates a binary target: **1** if tomorrow’s close > today’s close, otherwise **0**
- visualizes closing price trends over time
- ready for extension into ml modeling or dashboarding


---

## 📦 requirements
- python 3.9+
- pandas
- yfinance
- matplotlib

install dependencies:
pip install pandas yfinance matplotlib

---

## 💡 next steps
- add a machine learning model to predict `target`
- integrate with a sql database for storage
- build a streamlit dashboard for interactive analysis
