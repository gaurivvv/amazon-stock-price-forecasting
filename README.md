# 📈 Amazon Stock Price Forecasting using LSTM

A Deep Learning project that predicts Amazon stock closing prices using **Long Short-Term Memory (LSTM)** neural networks.  
This project applies **Time Series Forecasting** techniques on historical stock market data to analyze trends and predict future stock prices.

---

# 🚀 Project Overview

Stock market prediction is one of the most challenging problems in financial analysis due to its dynamic and non-linear nature.

In this project, an LSTM-based Deep Learning model is trained on Amazon historical stock data to:

✅ Learn stock price patterns  
✅ Forecast future closing prices  
✅ Visualize predicted vs actual trends  
✅ Evaluate model performance using regression metrics  

---

# 🧠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

# 📂 Project Structure

```bash
amazon-stock-price-forecasting/
│
├── datasets/
│   └── AMZN.csv
│
├── images/
│   ├── prediction_graph.png
│   └── loss_graph.png
│
├── model/
│   └── amazon_lstm_model.h5
│
├── notebook/
│   └── amazon_stock_forecasting.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📊 Dataset

The dataset contains historical stock price data of Amazon including:

- Open Price
- High Price
- Low Price
- Close Price
- Volume

The model primarily uses the **Closing Price** column for forecasting.

---

# 🔄 Workflow

## 1️⃣ Data Preprocessing
- Loading dataset
- Selecting closing prices
- Normalization using MinMaxScaler
- Creating time-series sequences

---

## 2️⃣ LSTM Model Building
The model consists of:

- LSTM Layers
- Dropout Layers
- Dense Output Layer

The network learns temporal dependencies from historical stock prices.

---

## 3️⃣ Model Training
The model is trained using:

- Adam Optimizer
- Mean Squared Error Loss Function

---

## 4️⃣ Prediction & Visualization
The trained model predicts stock prices on test data and compares:

- Actual Prices
- Predicted Prices

using graphical visualization.

---

# 📉 Model Performance

Evaluation Metrics Used:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

These metrics help evaluate forecasting accuracy.

---

# 📷 Results

## 🔹 Prediction Graph

![Prediction Graph](images/prediction_graph.png)

---

## 🔹 Training Loss Graph

![Loss Graph](images/loss_graph.png)

---

# 🔮 Future Improvements

- GAN-based Stock Prediction
- Multi-stock Forecasting
- Sentiment Analysis Integration
- Streamlit Web Application
- Real-time Stock Prediction
- Candlestick Chart Visualization

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/gaurivvv/amazon-stock-price-forecasting.git
```

Move into project folder:

```bash
cd amazon-stock-price-forecasting
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook using Jupyter Notebook or Google Colab.

---

# 📌 Key Learning Outcomes

This project helped in understanding:

- Time Series Forecasting
- Deep Learning Concepts
- LSTM Networks
- Data Preprocessing
- Neural Network Training
- Model Evaluation
- Financial Data Analysis

---

# 👩‍💻 Author

## Gauri

B.Tech AIML Student passionate about:
- Artificial Intelligence
- Machine Learning
- Deep Learning
- Data Science

---

# ⭐ If you found this project useful, consider giving it a star!
