# Predicting Electric Vehicle Resale Value and Maintenance Cost Using Machine Learning
A Machine Learning Framework for Maintenance Cost and Resale Value
In order to determine the resale value and maintenance costs of electric vehicles (EVs), this research uses a data-driven methodology. The system assesses different regression models using a dataset of 3,000 cars and 25 factors to offer practical insights for the EV market.
# Overview of the Project
Understanding depreciation and lifespan costs is essential as the EV market grows. In order to estimate vehicle value using ensemble learning approaches, this project examines the relationship between battery health, usage trends, and regional characteristics.
# Features & Dataset
A structured dataset of 3,000 electric vehicles with 25 characteristics is used to train the model. These variables include: • Battery Metrics: Capacity ($kWh$), Battery Health (%), and Range.
• Usage Information: Mileage, and Usage Type (Private/Commercial).
• Contextual Information: Region, and Vehicle Year.
# Model Performance
We assessed four regression models. Because of its better generalisation on unknown data, Gradient Boosting turned out to be the most reliable for practical use, even though Random Forest demonstrated the best training fit.
| Model | Test $R^2$ | Test RMSE (USD) | Status |
| :--- | :--- | :--- | :--- |
| **Gradient Boosting** | **0.7617** | **2,702.87** | **Best Generalizer** |
| Random Forest | 0.7479 | 2,779.80 | High Training Fit |
| Linear Regression | 0.7303 | 2,875.22 | Stable/Baseline |
| SVR | 0.0900 | 5280.17 | Poor Performance |
