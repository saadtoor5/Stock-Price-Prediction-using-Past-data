# 📈 Stock Price Prediction using Past Data

Predict future stock closing prices using historical data and a linear regression model.

---

## 🧠 About the Project

This beginner-friendly machine learning project demonstrates how to build a regression model that forecasts stock prices using past data. The model is trained with historical stock price data using the **Linear Regression** algorithm from `scikit-learn`. It also includes a visualization of actual vs. predicted values and an interactive prediction feature for future dates.

---

## 🚀 Features

* 🧹 Clean and preprocess date features for ML
* 📊 Train a Linear Regression model
* 📉 Evaluate performance with Mean Squared Error and R² Score
* 🔍 Visualize actual vs predicted closing prices
* ⏳ Predict future stock prices using a date input

---

## 🛠️ Tech Stack

* Python 3.x
* pandas
* scikit-learn
* matplotlib

---

## 📁 Project Structure

```
stock-price-prediction/
├── stock_prediction.py         # Main script
├── stock_prediction.ipynb      # Jupyter notebook file     
├── README.md                   # Project overview
├── LICENSE                     # MIT License
├── requirements.txt            # Required libraries
├── images/
│   └── training.png # Output chart visualization
└── stock_prices_500.csv        # Sample stock price data
```

---

## 💻 How to Run

1. **Clone the Repository**

```bash
git clone https://github.com/saadtoorx/stock-price-prediction.git
cd stock-price-prediction
```

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Script**

```bash
python stock_prediction.py
```

4. **Input a Future Date** when prompted (format: `YYYY-MM-DD`) to get a predicted closing price.

---

## 📷 Sample Output

![Prediction Plot](images/actual_vs_predicted.png)

---

## 🧾 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

Made with ❤️ by [@saadtoorx](https://github.com/saadtoorx)

Feel free to fork the repo, explore the code, and drop a ⭐ if you found it useful!
