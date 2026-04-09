# Gold Price Forecasting and Investment Strategy using Machine Learning & Macroeconomic Indicators

<div align="center">

# Gold Price Forecasting & Intelligent Investment Strategy

### Using Machine Learning, Time-Series Forecasting, and Macroeconomic Signals

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)]()
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)]()
[![Status](https://img.shields.io/badge/Status-Research%20Project-success)]()
[![Domain](https://img.shields.io/badge/Domain-Finance%20%7C%20Economics%20%7C%20AI-gold)]()

> “Can gold prices be forecasted before the market reacts?”

A research-oriented financial intelligence project that predicts gold prices by combining historical price movements with macroeconomic indicators such as inflation, stock market trends, and currency strength.

</div>

---

## Abstract

Gold has historically been considered a safe-haven asset during periods of inflation, market uncertainty, and geopolitical stress. However, most investment decisions are still made reactively — after the price movement has already occurred.

This project develops an end-to-end machine learning framework capable of forecasting future gold prices and transforming those forecasts into an actionable investment strategy.

Unlike conventional forecasting models that rely only on past gold prices, this project incorporates macroeconomic indicators including:

* Inflation trends
* Equity market behaviour
* USD strength
* Lagged gold prices
* Rolling averages and momentum
* Cross-market relationships

The objective is not only to improve predictive accuracy, but also to answer an economically meaningful question:

> Which factors truly drive gold prices, and how can those insights be converted into a smarter investment decision?

---

## Why This Project Stands Out

Most academic projects stop at predicting a number.

This project goes beyond prediction and builds a complete decision-making system:

* Forecasts gold prices using multiple machine learning models
* Studies how macroeconomic indicators influence gold
* Compares statistical and non-linear learning approaches
* Converts forecasts into Buy / Hold / Sell recommendations
* Bridges finance, economics, and data science in one integrated framework

This makes the project relevant not only for data science, but also for:

* Investment Research
* Quantitative Finance
* Portfolio Management
* Financial Economics
* MBA / IIM Internship Evaluation

---

## Research Questions

1. Which macroeconomic variables influence gold prices the most?
2. Can machine learning outperform traditional historical-trend methods?
3. Does adding external economic indicators improve forecast accuracy?
4. How can predictions be translated into a practical investment strategy?

---

## Problem Statement

Develop a machine learning-based framework that predicts future gold prices and recommends an investment action using macroeconomic indicators.

### Input Variables

| Variable              | Description                       |
| --------------------- | --------------------------------- |
| Gold Price            | Historical gold closing price     |
| NIFTY / Equity Index  | Proxy for market sentiment        |
| USD Index             | Measures US Dollar strength       |
| Inflation / CPI Proxy | Captures purchasing power erosion |
| Lag Features          | Previous gold price values        |
| Moving Averages       | Long-term trend indicators        |
| Rolling Volatility    | Measures market uncertainty       |

### Output

* Predicted future gold price
* Forecast evaluation metrics
* Buy / Hold / Sell recommendation

---

## Methodology

```text
Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
Correlation & Economic Interpretation
      ↓
Machine Learning Model Training
      ↓
Prediction & Evaluation
      ↓
Investment Strategy Design
```

---

## Exploratory Data Analysis

The project begins by understanding how gold behaves across different economic conditions.

### EDA Includes

* Gold price trend analysis
* Correlation matrix between macroeconomic variables
* Gold vs stock market comparison
* Gold vs USD relationship
* Detection of volatility and structural changes
* Rolling averages and trend persistence

### Key Insights

* Gold generally rises during periods of uncertainty
* A stronger USD often pushes gold prices lower
* Falling equity markets increase gold demand
* Lagged gold prices have strong predictive power

---

## Feature Engineering

Raw financial data is transformed into meaningful predictive features.

### Engineered Features

```python
Lag_1, Lag_3, Lag_7
Moving_Average_7
Moving_Average_30
Rolling_Volatility
Monthly_Return
USD_Change
NIFTY_Return
Inflation_Proxy
```

These features allow the model to capture:

* Momentum
* Market cycles
* Volatility shocks
* Delayed impact of macroeconomic changes

---

## Machine Learning Models Used

| Model                       | Purpose                           |
| --------------------------- | --------------------------------- |
| Linear Regression           | Baseline model                    |
| Random Forest Regressor     | Captures non-linear relationships |
| XGBoost / Gradient Boosting | Improves predictive accuracy      |
| Support Vector Regression   | Handles complex trend boundaries  |
| LSTM *(Future Scope)*       | Sequential time-series learning   |

---

## Evaluation Metrics

| Metric   | Meaning                     |
| -------- | --------------------------- |
| MAE      | Average forecasting error   |
| RMSE     | Penalises larger mistakes   |
| R² Score | Measures variance explained |
| MAPE     | Percentage prediction error |

---

## Investment Strategy Layer

| Forecast Result                                       | Suggested Action       |
| ----------------------------------------------------- | ---------------------- |
| Predicted price > Current price by significant margin | Buy                    |
| Predicted price approximately equal to current price  | Hold                   |
| Predicted price < Current price                       | Sell / Reduce Exposure |

Example:

```text
Current Gold Price     : ₹72,000
Predicted Gold Price   : ₹75,500
Expected Upside        : +4.8%
Decision               : BUY
```

---

## Tech Stack

```text
Python | Pandas | NumPy | Matplotlib | Seaborn
Scikit-Learn | XGBoost | Jupyter Notebook
```

---

## Repository Structure

```text
 Gold-Price-Forecasting/
│
├── data/
├── notebooks/
│   └── Gold_Price_Forecasting.ipynb
├── images/
├── models/
├── README.md
└── requirements.txt
```

---

## Results

* Macroeconomic indicators improved prediction accuracy
* Random Forest and XGBoost outperformed traditional methods
* Gold prices showed strong sensitivity to market uncertainty and currency movement
* The investment strategy successfully converted model forecasts into actionable recommendations

---

## Future Scope

* Live gold price integration
* News sentiment analysis
* LSTM / Transformer forecasting
* Streamlit dashboard
* Real-time buy/sell alerts

---

## Author

Nithyasri Suresh

Aspiring Business Scientist | Finance & Economics Enthusiast | Machine Learning Researcher

* LinkedIn:(https://www.linkedin.com/in/nithyasri-suresh-4ab928375?utm_source=share_via&utm_content=profile&utm_medium=member_ios)
* Email: nithyasrisuresh132@gmail.com

---

> This repository reflects a combination of machine learning, economics, and investment strategy — designed not just to predict prices, but to support better financial decisions.
