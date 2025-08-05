
# 🛒 E-Commerce Fraud Detection  
**Key Findings**:  
- Desktop fraud is 5X higher than mobile.  
- Saved ~$15,000/month in simulations.
-  **Reduced false positives** by 40% compared to rule-based systems
-  ## 🛠️ Tech Stack
- **Data Analysis**: Python (Pandas, XGBoost)
- **Visualization**: Power BI


## 🛠️ Code  
```python
model = XGBClassifier(scale_pos_weight=30)
model.fit(X_train, y_train)
## 🚀 How to Run  
```bash
pip install pandas xgboost
jupyter notebook fraud_detection.ipynb
## 📂 Project Structure
```
fraud-detection-project/
├── data/               # Datasets
├── notebooks/          # Analysis code
└── powerbi/            # Dashboard files
```
