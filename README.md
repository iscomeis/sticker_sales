# **Sales Prediction Using ML Regression Models**

- This study dives into a detailed analysis of sticker sales data, leveraging machine learning regression techniques to forecast performance effectively. Inspired by the [Kaggle Playground Series - Season 5, Episode 1](https://www.kaggle.com/competitions/playground-series-s5e1/overview), this project aims to evaluate various models and extract meaningful insights from the dataset.

- While **R² Score** will provide a measure of how well the models explain the variability in sales data, our primary focus lies on **Mean Absolute Percentage Error (MAPE)**. 

### **Highlights of the Workflow**
1. **Feature Engineering**:
    - Incorporation of custom features such as splitting the date column into `year`, `month`, and `day` for temporal analysis.
    - Encoding categorical variables like `country`, `store`, and `product` to allow models to understand their impact on sales.

2. **Data Preprocessing with KNN Imputation**:
    - Missing values in the target variable (`num_sold`) will be carefully handled using the **K-Nearest Neighbors (KNN) imputer**, ensuring no valuable data is lost.

3. **Exploration of Machine Learning Models**:
    - A range of regression models will be employed, including:
        - **Linear Regression**
        - **Random Forest Regressor**
        - **XGBoost Regressor**
        - **Gradient Boosting Regressor**
    - Each model will be evaluated based on both **R² Score** and **MAPE**, with MAPE serving as the decisive performance metric.

4. **Insightful Visualizations**:
    - Elegant and insightful graphs will be crafted to:
        - Showcase model performance metrics.
        - Analyze feature importance for interpretability.
        - Visualize actual vs. predicted sales for the top-performing model.
