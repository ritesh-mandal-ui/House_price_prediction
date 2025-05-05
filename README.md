# House_price_prediction
House Price Prediction using AI/ML
📌 Project Overview:
This project implements a machine learning model to predict house prices based on various features such as area, number of bedrooms, location, and more. It applies data preprocessing, feature engineering, and predictive modeling to provide accurate price estimations.
📊 Dataset Information
Source: The dataset used for training is collected from real estate websites, public datasets like Kaggle, and government housing records.

Features Used:

area (sq ft): Size of the house

bedrooms: Number of bedrooms

location: Geographic region (if applicable)

bathrooms: Number of bathrooms

age_of_property: Age of the house (years)

floor_number: Floor level for apartments

amenities: Features like swimming pool, parking, garden
Dataset Preprocessing:
✅ Handled missing values using mean/mode imputation ✅ Scaled numerical values using StandardScaler for better model performance ✅ Applied one-hot encoding for categorical variables (e.g., location, amenities) ✅ Removed outliers to improve accuracy
🧠 Model Details & Improvements
Machine Learning Techniques Used
✅ Linear Regression (Base Model) ✅ Decision Trees (Improvement with feature selection) ✅ Random Forest (Better accuracy & generalization) ✅ XGBoost (Final optimized model for prediction)

Hyperparameter Tuning
Used GridSearchCV to optimize model parameters

Fine-tuned learning rate, depth, and number of estimators

Evaluation Metrics
📉 Mean Absolute Error (MAE): Measures prediction errors 📈 R² Score: Evaluates model accuracy
