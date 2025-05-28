________________________________________
🌾 Crop Yield Prediction using Machine Learning Regression Models
 
 ![download - 2025-05-29T020446 727](https://github.com/user-attachments/assets/4a10f7d6-fe0d-4df9-91b5-b25026dc2b8f)
![download - 2025-05-29T020427 433](https://github.com/user-attachments/assets/bd2be959-b3b0-4346-9eb4-c9c4db69dfc4)

 
📌 Overview
This project presents a comprehensive benchmarking of machine learning regression models to predict crop yield (tons) from a variety of agronomic and farm-level inputs, including soil properties, irrigation types, pesticide/fertilizer usage, and seasonality.
We train and evaluate 14 supervised learning models, optimize them via GridSearchCV, and visualize both performance and error behavior using scatter and residual plots.
________________________________________
📊 Models Implemented
•	🔹 Linear Regression, Ridge, Lasso, ElasticNet, Bayesian Ridge
•	🌲 Random Forest Regressor
•	⚡ XGBoost Regressor
•	💡 LightGBM Regressor
•	🐈 CatBoost Regressor
•	🔁 AdaBoost and Gradient Boosting
•	🧠 MLP Regressor (Neural Network)
•	📈 SVR and KNN Regressor
All models were evaluated using MSE and R² Score and tuned using cross-validated grid search where applicable.
_![image](https://github.com/user-attachments/assets/9394e168-97f9-46f7-8304-402d060df621)
_______![image](https://github.com/user-attachments/assets/9fdafca6-5845-4b43-a7ef-37a11cf8c465)
________________________________
🧪 Dataset
The dataset consists of 50 real-world samples with the following features:
•	Crop_Type
•	Farm_Area(acres)
•	Irrigation_Type
•	Fertilizer_Used(tons)
•	Pesticide_Used(kg)
•	Soil_Type
•	Season
•	Water_Usage(cubic meters)
•	🔺 Target: Yield(tons)
Categorical columns are encoded and feature scaling is applied as needed for sensitive models (e.g., SVR, MLP).
________________________________________
📈 Evaluation & Visualization
Each model's performance was visualized through:
•	✅ Predicted vs Actual Yield Plots
•	📉 Residual Error Plots
•	📊 Error Distribution Histograms
•	🔍 Best models identified through GridSearchCV tuning
________________________________________
🧰 Tools & Libraries
•	scikit-learn
•	xgboost, lightgbm, catboost
•	matplotlib, seaborn
•	pandas, numpy
________________________________________
🚀 Getting Started
git clone https://github.com/your-username/crop-yield-regression.git
cd crop-yield-regression
pip install -r requirements.txt
python model_training.py
________________________________________
📝 Results Summary
Model	MSE	R² Score
CatBoost	128.93	0.19
Random Forest	137.36	0.14
AdaBoost	137.12	0.14
LGBM	142.92	0.10
XGBoost	143.04	0.10
________________________________________
________________________________________
👨‍🔬 Author
Santanu Banerjee


