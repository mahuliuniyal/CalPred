# CalPred 🧮🔥

## 📌 Project Overview
**CalPred** is a machine learning-based calorie prediction system that estimates the number of calories burned during exercises based on numerical input features. The model was trained using **real-world exercise datasets from Kaggle** and leverages efficient ML techniques to generate accurate calorie predictions.

This project was developed entirely in **Google Colab**, with a focus on easy deployment and reproducibility.

## 📊 Dataset
- Sourced from [Kaggle](https://www.kaggle.com/)
- Contains information such as:
  - Age
  - Height
  - Weight
  - Duration of exercise
  - Heart rate
  - Body temperature
  - Calories burnt

## 🧰 Technologies & Libraries Used
| Library | Purpose |
|--------|---------|
| `pandas` | Data manipulation and preprocessing |
| `numpy` | Numerical operations |
| `matplotlib`, `seaborn` | Visualization of trends and insights |
| `xgboost` | ML model for calorie prediction |
| `sklearn` | Train/test split, metrics (MAE, RMSE, R²), model validation |
| `kaggle` | Dataset access via API (if used) |
| `joblib` / `pickle` | (If used) Model saving/loading |

## 🛠 How to Run
1. Open `CalPred.ipynb` in [Google Colab](https://colab.research.google.com/).
2. (Optional) Mount Google Drive if dataset is stored there.
3. Install any missing dependencies:
   `!pip install xgboost`
4. Run cells sequentially to:
   - Load and preprocess dataset
   - Train the XGBoost regression model
   - Evaluate accuracy and visualize results

## 🎯 Features
- Calorie prediction based on physiological input
- Exploratory Data Analysis (EDA) on fitness metrics
- Model evaluation using RMSE, MAE, and R²
- Visual insights via charts

## 📂 Files
- `CalPred.ipynb`: The main notebook
- `README.md`: Project documentation

## 🙋 Author
**Mahuli Uniyal**

## 📜 License
This project is licensed under the MIT License.
