# Machine-Learning-module-end-project

# 🚗 Car Price Prediction – Machine Learning Project

📌 Project Motive
A Chinese automobile company aims to enter the US market by setting up local manufacturing and competing with US and European brands. To succeed, they need to understand the factors influencing car prices in the American market, which may differ significantly from the Chinese market.

# The goal of this project is to:

🔎 Identify the key variables affecting car prices.
📈 Build predictive machine learning regression models to estimate car prices.
💼 Provide insights that will help management manipulate design, strategy, and pricing to fit different market segments.
🌍 Support the company in understanding pricing dynamics of a new market for informed decision-making.
⚙️ Project Workflow
Problem Understanding

Defined the business problem and objective.
Understood the need to model car prices for market strategy.
Data Exploration & Preprocessing

Explored dataset for missing values, outliers, and data distribution.
Extracted new features (e.g., car brand from car name).
Encoded categorical variables using One-Hot Encoding.
Handled skewness and scaling where necessary.
Feature Engineering

Identified numerical and categorical variables.
Used feature importance (Random Forest) and RFE for feature selection.
Model Building

# Implemented and compared multiple regression models:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)
Applied GridSearchCV for hyperparameter tuning on Random Forest.

Model Evaluation

Evaluated models using R² Score, MSE, and MAE.
Compared base vs tuned models.
Visualized feature importance and residual errors.

# ✅ Final Insights & Conclusion

🏆 Best Model: Random Forest Regressor achieved the highest R² ≈ 0.96, explaining ~96% of car price variance.

❌ Worst Model: Support Vector Regressor performed poorly (negative R²), making it unsuitable for this dataset.

🔑 Key Drivers of Price: Engine size, curb weight, horsepower, car width, and fuel efficiency (mpg) strongly influenced pricing.

⚡ Tuning Impact: Hyperparameter tuning of Random Forest provided only marginal improvements, showing robustness of the base model.

# 💡 Business Implications:

Adjusting technical specifications (engine, horsepower, weight) can target desired price ranges.
Balancing fuel efficiency vs performance helps position cars for budget vs premium markets.
The model can simulate pricing strategies in new markets, guiding competitive decision-making.

# 🚀 Conclusion

This ML regression project not only delivers an accurate car price prediction model but also acts as a strategic decision-support tool. By linking technical features to pricing, management can confidently design cars, optimize business strategies, and adapt pricing models when entering the US automobile market.
