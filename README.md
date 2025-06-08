# 🌍 Air Quality Index (AQI) Prediction for Lahore

## 📌 Project Overview
This project predicts the **Air Quality Index (AQI)** for Lahore using machine learning models. The dataset includes historical weather and pollution data from **2019 to 2024**, allowing for accurate forecasting and analysis of air pollution trends.

## 📊 Dataset
- **Source:** Collected from multiple sources.
- **Years Covered:** 2019 - 2024
- **Target Variable:** `AQI_PM2.5`
- **Features Used:** Weather conditions, pollution levels, and other environmental factors.

## 🚀 Models Used & Performance
| Model | R² Score | MAE | RMSE |
|--------------------------|----------|-------|-------|
| **Linear Regression (Before Feature Engineering)** | 0.4127 | 0.2347 | 0.3335 |
| **Linear Regression (After Feature Engineering)** | 0.8299 | 0.1258 | 0.1814 |
| **Lasso Regression** | 0.8328 | - | - |
| **Random Forest (Before Hyperparameter Tuning)** | 0.8835 | 0.1109 | 0.1501 |
| **Random Forest (After Hyperparameter Tuning)** | 0.8879 | 0.1100 | 0.1473 |
| **XGBoost (Cross-Validation)** | 0.8316 | - | - |

## 📌 Feature Engineering
- **Lag Features** (Previous AQI values)
- **Rolling Averages**
- **Weather Interactions**
- **Multicollinearity Handling**

## 📈 Model Predictions Visualization
- Individual plots for each model’s predictions.
- Side-by-side comparison of actual vs. predicted values.

## 🛠 Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- **Jupyter Notebook** for analysis & modeling

## 📦 Installation & Usage
```bash
# Clone the repository
git clone https://github.com/your-username/AQI_Prediction.git
cd AQI_Prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
```

## 📌 Future Improvements
- **Real-time AQI Forecasting**
- **Integration with IoT Sensors**
- **Deep Learning Models (LSTMs, CNNs)**

## 📝 Author
- **Ammar Shahid**

📌 If you find this project useful, feel free to ⭐ star this repo!
