
# 📈 Stock Forecast App

This Streamlit app predicts stock prices for selected companies using historical data from Yahoo Finance and the Facebook Prophet forecasting model. It provides a user-friendly interface for visualizing stock trends and making future predictions.

---

## 🚀 Features

- Select stocks from a predefined list (`GOOG`, `AAPL`, `MSFT`, `GME`).
- View raw stock data from Yahoo Finance.
- Interactive time-series plots with rangeslider functionality.
- Predict future stock prices for up to 4 years using the Prophet model.
- Visualize forecast trends and components (trend, weekly, yearly).

---

## 🛠️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/stock-forecast-app.git
   cd stock-forecast-app
   ```

2. **Set Up Python Environment**
   - It's recommended to use a virtual environment:
     ```bash
     python -m venv env
     source env/bin/activate  # On Windows: .\env\Scripts\activate
     ```

3. **Install Dependencies**
   ```bash
   pip install streamlit prophet yfinance plotly
   ```

4. **Run the App**
   ```bash
   streamlit run app.py
   ```

---

## 📋 Usage

1. Launch the app using the command above.
2. Select a stock from the dropdown menu (e.g., `GOOG`, `AAPL`).
3. Choose the number of years for prediction (1 to 4).
4. View raw historical stock data in a table format.
5. Explore interactive plots for stock opening/closing prices.
6. Analyze forecasted trends and seasonal components.

---

## 📂 Project Structure

```
stock-forecast-app/
├── app.py             # Main Streamlit app code
├── README.md          # Project documentation
└── requirements.txt   # List of required Python libraries
```

---

## 📊 Example Output

### Raw Data Table
View the latest historical data for the selected stock.

### Time Series Plot
Interactive plot with opening and closing stock prices.

![Time Series Plot](https://via.placeholder.com/800x400?text=Time+Series+Plot)

### Forecast Plot
Future stock price predictions using Prophet.

![Forecast Plot](https://via.placeholder.com/800x400?text=Forecast+Plot)

---

## 🛑 Troubleshooting

### Common Issues

1. **`ModuleNotFoundError: No module named 'prophet'`**
   - Ensure you installed the `prophet` package instead of `fbprophet`:
     ```bash
     pip install prophet
     ```

2. **Missing or Incomplete Data**
   - The app handles missing data by dropping null values. If you encounter unexpected issues, verify the fetched data manually.

3. **Graph Rendering Problems**
   - Ensure you installed all dependencies for `plotly` and `streamlit` correctly.

---

## 🧑‍💻 Credits

This project is inspired by tutorials learned from YouTube. A special thanks to the creators who made learning easy and engaging!

---

## 📄 License

This project is licensed under the MIT License. Feel free to use and modify the code as needed.

---

## 💡 Acknowledgments

- [Streamlit](https://streamlit.io/)
- [Yahoo Finance API](https://pypi.org/project/yfinance/)
- [Prophet](https://facebook.github.io/prophet/)
