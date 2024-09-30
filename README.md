# Predictive Modeling of Concrete Compressive Strength Using Machine Learning
In this project, the goal was to develop predictive models for estimating the compressive strength of concrete, a critical parameter in civil engineering, using machine learning techniques. The project focused on leveraging the recent advancements in machine learning to address the challenge of accurately predicting concrete strength, which is essential for ensuring the structural integrity of civil infrastructures while optimizing material costs and environmental impacts.

**1. Exploratory Data Analysis:**

-Constructed histograms to visualize the distribution and central values of all variables.
- Employed boxplots to identify potential outliers within the variables.
- Utilized pair plots to examine the pairwise relationships between the independent variables.
- Applied a heatmap to assess the correlation between predictor variables.

**2. Data Preparation & Feature Engineering:**

- Identified and addressed duplicate entries, missing values, and potential outliers.
- Applied a standard scaler to rescale the data appropriately.
- Handled issues related to zero values in the dataset.
- Addressed Imbalance in the class distribution.

**3. Modeling & Evaluation:**

- The dataset was split into train (70%) and test (30%) sets.
- Built predictive models using K-Nearest Neighbor Regressor, Random Forest, and XGBoost techniques.
- Utilized a voting regressor to combine predictions from heterogeneous models (KNN Regressor, Random Forest, XGBoost).
- Compared results based on criteria such as Root Mean Squared Error (RSME), Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared accuracy to identify the best and worst performing models.

Result: The Random ForestRegressor has the lowest RMSE, MAE, and MSE, and the highest R2 accuracy, indicating that it is the best model for this project. On the other hand, the KNeighborsRegressor is the worst-performing model for this project.
