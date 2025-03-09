🚗 Go Auto - AI-Powered Mileage Classification

📌 Automating Mileage-Based Pricing & Inventory Decisions Using Machine Learning

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🏆 Project Overview

In the automotive industry, mileage significantly impacts a vehicle’s resale value, demand, and marketability. However, dealerships lack automated systems to classify mileage bands, leading to suboptimal pricing and inefficient inventory management.

This project introduces an AI-driven Mileage Classification Model, powered by XGBoost, to categorize vehicles into Low, Medium, and High mileage bands with 95% accuracy. By leveraging feature engineering, data preprocessing, and hyperparameter tuning, this solution enables dealerships to make data-driven decisions for pricing, marketing, and inventory optimization.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🚀 Key Features

✅ 📊 AI-Driven Mileage Classification: Predicts whether a vehicle falls into Low, Medium, or High mileage bands
✅ 🔍 Advanced Data Processing: Handles missing values, outlier detection, and feature scaling
✅ 📈 Exploratory Data Analysis (EDA): Analyzes pricing trends, dealership performance, and regional demand
✅ 🏎️ Feature Engineering: Introduces Mileage Per Year, Price Drop Frequency, and Sales Velocity
✅ ⚡ Optimized XGBoost Model: Achieves 95% accuracy using GridSearchCV for hyperparameter tuning
✅ 📊 Data Visualization: Provides insights into mileage, pricing, and dealership sales trends

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📂 Dataset Overview

📌 Data Source:
✔️ Go Auto Inventory Listings (Active & Sold Vehicles)
✔️ Integrated with Canadian Black Book (CBB) API

📌 Key Attributes Used:
✔️ Vehicle Details: Year, Make, Model, Mileage, Price
✔️ Sales Insights: Days on Market, Price Adjustments
✔️ Dealership Information: Location, Stock Type, VIN-based Features

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Exploratory Data Analysis (EDA) Insights

📌 Mileage vs. Price Trends:
	•	Higher mileage vehicles sell for lower prices, but brands like Toyota & Ford retain value better
	•	Low-mileage vehicles are sold at a premium

📌 Regional Sales Patterns:
	•	Certain dealership locations outperform others in selling low-mileage vehicles
	•	Identifying postal code-based demand helps in inventory optimization

📌 Days on Market Analysis:
	•	Low-mileage vehicles tend to sell faster than high-mileage ones
	•	Some vehicle makes/models have higher resale demand

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🤖 Machine Learning Model

✔️ Model Used: XGBoost (Extreme Gradient Boosting)
✔️ Problem Type: Multi-Class Classification
✔️ Target Variable: Mileage Band Classification (Low, Medium, High)

🔹 Feature Engineering:
✔️ Mileage Per Year = Total Mileage ÷ Vehicle Age
✔️ Price Adjustments Before Sale
✔️ Stock Type (New/Used)
✔️ Regional Demand Analysis

🔹 Model Performance:
✔️ Accuracy: 95%
✔️ Optimized using: GridSearchCV for hyperparameter tuning
✔️ Class Imbalance Handling: SMOTE

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠 Tech Stack

🚀 Python | Scikit-Learn | Pandas | Matplotlib | Seaborn | XGBoost 
