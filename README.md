# gold-forecast-using-lstm

An LSTM-based deep learning project for predicting gold trading signals (Buy, Sell, No Action) in the Forex market. The model is trained on a custom dataset enriched with Ichimoku and technical indicators, and hyperparameters are optimized using Optuna. Final model performance is evaluated using classification metrics and visualized with a confusion matrix.

# 📈 Gold Trading Signal Prediction using LSTM & Optuna

This project focuses on forecasting trading signals (Buy, Sell, No Action) for **XAUUSD (Gold in Forex)** using LSTM-based deep learning architecture and Optuna for hyperparameter optimization.

---

## 📌 Project Highlights

- 🔍 Forecasting gold price action in Forex using historical data
- 🧠 LSTM deep learning architecture
- ⚙️ Hyperparameter tuning with **Optuna**
- ⚖️ Class balancing with sample weights
- 📊 Evaluation with classification report and confusion matrix
- 💾 Model and Scaler saved for deployment or future use

---

## 🧪 Technologies Used

- Python 3.x
- TensorFlow / Keras
- Optuna
- Pandas, Numpy, Matplotlib, Seaborn
- Scikit-learn

---

## 🗂️ Dataset

The dataset includes:
- OHLC data (Open, High, Low, Close)
- Ichimoku components (tenkan, kijun, senkou_a, senkou_b, komo, etc.)
- Custom label: `b` (Buy), `s` (Sell), `n` (No Action)

> ⚠️ Note: The dataset is not included in this repo due to size/privacy. You can modify the code to load your own CSV.

---

## 🔧 Project Structure

```bash
📁 project-root/
├── data/                       # CSV dataset (not included)
├── best_lstm_evolution_model_1.h5
├── minmax_scaler_1.pkl
├── LSTM_Model.ipynb or LSTM_Model.py       # Main training script
├── README.md                   # (You're here)
└── requirements.txt
```


## 🚀 How to Run
1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Connect to Google Drive (if using Colab) and ensure the dataset path is correct.
3. Run Jupiter Notebook file
4. Final results:

Classification Report
Confusion Matrix
Trained .h5 model
Scaler .pkl file

## 📊 Sample Output
Confusion matrix and classification metrics are printed after training.

## 📜 License
MIT License


## 🤝 Contributions
Pull requests are welcome! For major changes, please open an issue first.




