# Predictive-Analytics-on-Sports-Data-using-R
This project aims to predict the number of points scored by NBA players during the 2017 NBA regular season based on various player statistics.

## Key Skills and Techniques Showcased
### 1. Data Preprocessing
* Data Cleaning: The project starts by loading and cleaning the dataset, handling missing values, and ensuring data quality.

### 2. Exploratory Data Analysis (EDA)
* Data Visualization: EDA includes visualizing the distribution of variables, detecting outliers, and understanding the relationships between predictors.

### 3. Linear Regression Modeling
* Model Building: A linear regression model is developed to predict points scored by NBA players.
* Variable Selection: Stepwise selection based on AIC/BIC criteria is applied to choose the most relevant predictors.
* Multicollinearity Handling: Techniques like Variance Inflation Factor (VIF) analysis are used to manage multicollinearity.

### 4. Model Diagnostics and Validation
* Assumption Checking: Model assumptions, including linearity, independence, homoscedasticity, and normality, are assessed through diagnostic plots and statistical tests.
* Model Validation: Cross-validation is employed to validate the final model's performance on testing data.
* Influential Points Identification: Cook's Distance and DFFITS are used to detect influential points.

## Findings
* The final model explains 84.24% of the variation in points scored.
* Key predictors like assists, steals, rebounds, and turnovers significantly impact points scored.

## Limitations
* Multicollinearity remains a challenge, affecting the precision of coefficient estimates.
* Slight violations of constant variance assumptions are observed.

## Future Improvements
* Explore advanced techniques for handling multicollinearity.
* Investigate alternative transformations for constant variance.
