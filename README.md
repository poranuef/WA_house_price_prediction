# Washington House Price Prediction

![](https://s.yimg.com/ny/api/res/1.2/ibw4qRyWocPKXAdgY31Pjw--/YXBwaWQ9aGlnaGxhbmRlcjt3PTY0MDtoPTM2MA--/https://media.zenfs.com/en/gobankingrates_644/e68c560a2c32260d043ba09a717e5b60)

This project focuses on predicting house prices in King County, Washington using various machine learning algorithms. The analysis helps both buyers and sellers make informed decisions by providing accurate price predictions based on multiple property features.

## Problem Statement

- Sellers struggle to set appropriate house prices
- Buyers need reliable information for decision-making
- Need for data-driven pricing recommendations in the real estate market

## Project Overview

The goal of this project is to predict house prices using features such as square footage, location, and property conditions. The notebook outlines the following steps:

1. Data Importation and Cleaning
2. Exploratory Data Analysis (EDA)
3. Handling Outliers
4. Model Building and Validation

## Dataset Description

The analysis uses a dataset from Kaggle containing 4,600 records with 18 features including:

- **Date**			    Date of the listing of the house​
- **Price**			    Listing price of the property​
- **Bedrooms**		  Number of bedrooms in the house​
- **Bathrooms**		  Number of bathrooms in the house​
- **Sqft Living**		Living area in square feet​
- **Sqft Lot**		  Lot area in square feet​
- **Floors**			  Number of floors in the house​
- **Waterfront**		Indicates if property is waterfront​
- **View**		     	Type of view from the property​
- **Condition**	  	Condition of the property​
- **Sqft Above** 		Square feet above ground level​
- **Sqft Basement** Square feet of the basement​
- **Yr Built**	  	Year the property was built​
- **Yr Renovated**  Year of renovation​
- **Street**      	Street address of the property​
- **City**	   			City where the property is located​
- **State/Zip**  	  State and ZIP code​
- **Country**    		Country of the property


## Exploratory Data Analysis (EDA)

Key findings during the EDA include:
- Visualization of feature distributions and relationships between variables.

### Outlier Handling

Outliers were addressed using the Interquartile Range (IQR) technique:
- Calculated the IQR for features.
- Removed data points outside the acceptable range.

## Modeling and Evaluation

The project implements regression models to predict house prices:

1. **Linear Regression**
2. **Ridge and Elastic Net**
3. **Lasso Regression**

### Best Performing Model

- **Lasso Regression**: Achieved the best results with the following metrics:
  - **R-squared**: 0.71
  - **MSE**: 22,562,992
  - **MAE**: 101,386

## Future Improvements

- Enhanced feature engineering
- Collection of additional relevant features
- Model optimization and tuning
- Integration of market trend data

