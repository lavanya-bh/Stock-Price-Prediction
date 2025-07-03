# Stock Market Price Prediction 📈

A machine learning project that predicts future stock prices using historical data and compares different regression models for performance.

## 🎯 Objective

Predict stock prices using historical market data and evaluate model performance to identify the most accurate prediction method.

## 📦 Dataset

- Historical stock data (likely includes Open, High, Low, Close, Volume)
- Sourced via financial APIs or CSV exports (e.g., Yahoo Finance)

## 🧰 Libraries & Tools

- Python  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib, Seaborn  
- LSTM (if implemented in extended version)  
- Optional: yfinance for data import

## 🔍 Workflow

1. **Data Preprocessing**  
   - Handling missing values  
   - Feature scaling (e.g., MinMaxScaler)  
   - Creating lag-based features

2. **Exploratory Data Analysis**  
   - Visualizations for trend, seasonality, and volume  
   - Correlation heatmaps

3. **Modeling Techniques**  
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
   - LSTM (optional)  
   - Model evaluation using MSE, RMSE, and R² Score

4. **Prediction & Visualization**  
   - Predicted vs actual price comparison  
   - Line charts to visualize forecast accuracy

## 🚀 How to Use

1. Clone this repository  
2. Open and run `Project_Stock_Market_Prediction- new.ipynb`  
3. Modify the ticker or dataset path for other stocks  
4. View model performance and choose the best predictor

## 📈 Example Output

- Actual vs Predicted price plots
- RMSE and R² comparison of models
- Insights into model accuracy and volatility trends

## 🔮 Future Enhancements

- Add deep learning models (LSTM/GRU)
- Integrate real-time stock price updates using `yfinance`
- Deploy via Streamlit for live forecasts

## 📁 File

- `Project_Stock_Market_Prediction- new.ipynb`: Complete code notebook with preprocessing, modeling, and evaluation

## 📝 License

This project is for educational purposes and is open-source under the MIT License.
