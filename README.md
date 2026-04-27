# 🌫️ Air Quality & Health Risk Prediction (India)

## 📌 Overview  
This project presents a statistically validated machine learning framework to predict **health risk levels based on air pollution exposure** across Indian cities. Using CPCB air quality data, the model incorporates **lagged exposure features** to capture delayed health effects and improves prediction accuracy.

---

## 🚀 Key Features  
- End-to-end statistical + machine learning pipeline  
- Lag-based feature engineering (1–3 day exposure effects)  
- Multiple statistical hypothesis tests for validation  
- Comparison of ML models (LR, KNN, SVM, Random Forest)  
- Random Forest achieving **~89.24% accuracy**  
- Feature importance analysis highlighting key pollutants  

---

## 🧠 Tech Stack  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Statsmodels  
- Matplotlib, Seaborn  

---

## 📂 Dataset  
- Source: CPCB (Central Pollution Control Board, India)  
- Time Range: **2015 – 2020**  
- Coverage: **26 cities, ~29,500 observations**  
- Pollutants Used:  
  - PM2.5, NO2, NH3, CO, SO2, O3, Benzene  

---

## ⚙️ Methodology  

### 1. Data Preprocessing  
- Removed duplicates and high-missing-value features  
- Multicollinearity reduction using **VIF analysis**  
- Median imputation for missing values  

### 2. Statistical Validation  
- Mann-Whitney U Test  
- Chi-Square Test  
- Kruskal-Wallis Test  
- Augmented Dickey-Fuller (ADF) Test  
- Logistic Regression Odds Ratios  

### 3. Feature Engineering  
- Created **lag features (lag1, lag2, lag3)**  
- Captured delayed health effects of pollution  

### 4. Model Training  
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Random Forest  

### 5. Evaluation Metrics  
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## 📈 Results  
- **Random Forest achieved highest accuracy: ~89.24%**  
- SVM: ~86.78%  
- KNN & Logistic Regression: ~85.7%  
- PM2.5 identified as the most influential pollutant (~50% importance)  
- Lag-1 features contributed the most (~45%)  

---

## 🔍 Key Insights  
- PM2.5 and CO are dominant drivers of health risk  
- Health risk varies significantly across cities  
- Lagged exposure improves predictive performance  
- Statistical validation strengthens model reliability  

---

## 📌 Applications  
- Smart city health monitoring systems  
- Air quality early warning systems  
- Public health decision support  
- Environmental risk analysis  

---

## 🔮 Future Work  
- Real-time prediction systems  
- Integration with weather and hospital data  
- Deep learning models (LSTM, Transformers)  
- Deployment as web/dashboard application  

---

## 📬 Contact  
**Naga Desa Vara Prasad Borra**  
📧 prasadborra9701@gmail.com  
