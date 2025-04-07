# 📈 Twitter Sentiment: Effect on Stock Prices

Welcome to our repository! This project explores the intersection of financial data and social media sentiment, explicitly investigating whether Twitter sentiment can enhance the prediction of stock price movements for major consumer-facing companies.

---

## 🧠 Project Overview

### **Can tweets predict stock price movements for consumer-facing companies?**  
We aimed to answer that question in this machine learning-driven research study.

We analyzed historical stock price data and Twitter sentiment for companies like **Netflix**, **Tesla**, **Google**, **Meta**, **AMD**, and more. Examining a variety of predictive models, we analyzed whether including sentiment scores improved prediction accuracy for short-term stock price movements.

This work culminated in a formal research paper, which includes our methodology, findings, and implications for both data science and financial forecasting.

---

## 🧪 What We Did

- Collected stock price data using Yahoo! Finance  
- Used a tweet dataset from 2022 for consumer-based companies  
- Applied FinBERT (a finance-focused NLP model) to classify tweet sentiment  
- Engineered features from both sentiment and historical price movements  
- Built and evaluated ML models for classification and regression (Logistic Regression, Random Forest, XGBoost, etc.)  
- Compared model performance with and without sentiment inputs  

---

## 💡 Key Insight
Sentiment can influence the market — but its predictive power depends on context and time.  
Our results showed that while sentiment sometimes improves model performance, its effect varies by company and timeframe. The takeaway? **Sentiment is a useful but nuanced signal**.

---

## 👥 Meet the Team

This project was a collaboration between four researchers:

- [Rithik Kulkarni](https://github.com/rithikkulkarni)
- [Ethan Goodman](https://github.com/EthanGoodman)
- [Jeff Powell](https://github.com/jeff-pow) 
- [Zeiad Yakout](https://github.com/zeiadyakout)

---

## 📂 Repository Structure

├── datasets/ # Various levels of cleaned and filtered datasets

├── finbert_labeling.ipynb # Initial sentiment labeling, separated for runtime efficiency

├── more_data_preprocessing.ipynb # yfinance utilization for extracting stock market features to prep model

├── basic_model.ipynb # Modeling & evaluation

└── README.md # You're here!

---

## 📄 Read the Paper
You can find our full research paper here (not linked yet!)

## 🙌 Thanks for Stopping By!
If you’re interested in data science, NLP, finance, or just enjoy seeing machine learning applied to the real world — we hope you find something useful here.
