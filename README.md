# 📰 News Sentiment & Stock Market Analysis (10 Academy - Week 1)

This project analyzes financial news headlines and their relationship to stock market movements. It is part of 10 Academy’s AI Mastery Sprint Week 1 challenge.

## 📁 Project Structure

news-sentiment-analysis/
├── data/ # Raw and processed CSV files
├── notebooks/
│ ├── 01_eda_sentiment.ipynb # EDA + sentiment analysis
│ └── 02_stock_price_analysis.ipynb # Technical indicator analysis
├── scripts/ # Future scripts (e.g. training, automation)
├── src/ # (Optional) Python modules
├── requirements.txt
├── README.md


## ✅ Completed Tasks

### Task 1: News Sentiment & Environment Setup
- Project created with virtual environment
- News data loaded and cleaned
- Headlines scored using NLTK’s VADER
- Sentiment labels added (positive / neutral / negative)
- GitHub repo initialized with task-1 branch

### Task 2: Technical Stock Analysis
- AAPL and other stocks loaded from Yahoo Finance
- Calculated:
  - SMA (20 & 50)
  - RSI (14)
  - MACD and Signal line
- Plotted indicators for trend analysis
- Notebook committed on task-2 branch

## 🚧 Next Steps (Task 3)
- Align headlines with stock price dates
- Label price direction (up/down)
- Analyze correlation between sentiment and price change

## 💻 Environment

- Python 3.10+
- Jupyter Notebook
- Libraries: pandas, matplotlib, seaborn, nltk, ta, yfinance



