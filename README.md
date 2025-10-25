
# 📈 Stock Market Analysis Project

Analyze and compare the performance of major tech companies using historical stock data and data science techniques.

## 🧠 Objective
To explore stock price trends, assess volatility, and uncover relationships between Apple (AAPL), Microsoft (MSFT), Netflix (NFLX), and Google (GOOG) using Python and machine learning.

## 🛠️ Tools & Technologies
- **Python**: Data manipulation and modeling
- **Pandas & NumPy**: Data cleaning and transformation
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Predictive modeling
- **Pandas Profiling**: Automated EDA
- **Jupyter Notebook**: Interactive analysis

## 📂 Dataset
- Historical daily stock prices from Feb 7, 2023 to May 5, 2023
- Columns: `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`, `Ticker`
- Stocks: AAPL, MSFT, NFLX, GOOG

## 📊 Key Analyses
### 1. Exploratory Data Analysis (EDA)
- Distribution of closing prices
- Boxplots to detect outliers
- Volume analysis by ticker
- Correlation matrix of price metrics

### 2. Feature Engineering
- 7-day and 30-day moving averages
- Rolling standard deviation for volatility

### 3. Inter-stock Correlation
- Pivoted data to compare closing prices across companies
- Heatmap of inter-stock relationships

### 4. Predictive Modeling
- Linear regression to forecast AAPL closing prices
- Evaluation using R² and RMSE

## 📈 Visualizations
- 📉 Closing Price Distribution
- 📦 Boxplot of Closing Prices
- 📊 Volume vs. Closing Price
- 🔗 Correlation Matrix
- 📊 Moving Averages and Volatility Trends
- 🔮 AAPL Price Prediction Plot

## 📌 Insights
- Strong positive correlation among price metrics
- Volume shows weak negative correlation with prices
- Netflix exhibits highest volatility
- Apple and Microsoft dominate in trading volume

## 🚀 How to Run
1. Clone the repository
2. Place `stocks.csv` in the root directory
3. Open `stock_market_analysis.ipynb` in Jupyter
4. Run all cells to reproduce the analysis

## 📁 Project Structure
```
├── stocks.csv
├── stock_market_analysis.ipynb
├── README.md
```

## 🧾 Author
**Jaydev Chole**  
MSc Data Science | Aspiring Data Analyst  
GitHub:https://github.com/jaydevchole
LinkedIn:(https://www.linkedin.com/in/jaydev-chole-b3313b327)
---


