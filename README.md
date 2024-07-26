# Linear-Regression

**Home Prices Prediction**
This project aims to predict home prices based on area using linear regression. The dataset used for training the model includes information about the area of houses and their corresponding prices.

**Dataset**
The dataset homeprices.xlsx contains two columns:
**area:** The area of the house in square feet.
**price:** The price of the house in US dollars.

**Steps**
**Data Cleaning and Preparation:**
Loaded the dataset and stripped any leading/trailing whitespace from column names.
Visualized the data using a scatter plot to understand the relationship between area and price.
**Model Training:**
Trained a linear regression model using the area as the independent variable and price as the dependent variable.
**Prediction:**
Predicted the price of a house given its area using the trained linear regression model.
Visualized the regression line on the scatter plot of the data.

**Prediction for New Data**
A new dataset predict_price_of_area.xlsx containing areas for which prices need to be predicted was used. The model predicted the prices for these areas and the results were added to the dataset.

**Visualization**
Scatter plots and regression lines were plotted to visualize the data and the fitted linear regression model.

**Exercise:** 
**Predicting Per Capita Income**
An additional exercise was conducted to predict Canada's per capita income based on historical data.

**Dataset**
The dataset canada_per_capita_income.csv contains two columns:
**year:** The year.
**per capita income (US$):** The per capita income in US dollars.

**Steps**

**Data Visualization:**
Plotted a scatter plot to visualize the relationship between year and per capita income.

**Model Training:**
Trained a linear regression model using year as the independent variable and per capita income (US$) as the dependent variable.

**Prediction:**
Predicted the per capita income for the year 2020 using the trained model.
Visualized the regression line on the scatter plot of the data.

**Dependencies**
pandas
numpy
matplotlib
scikit-learn
openpyxl (for reading Excel files)
