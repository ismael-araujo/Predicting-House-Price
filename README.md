# Kings County Housing Price Prediction

Author: Ismael Araujo

## Overview

![img](/seattle.jpg)

Using data exploration, feature engineering, and statistical test, I created a model to predict prices of houses in Kings County, Seattle. This repository contains files that will lead to a final prediction that have not been trained and it did not contain prices.

### Deliverables
1. GitHub repository with all the files
2. Jupyter notebook with EDA, Feature Engineering, statistical tests, and model evaluation.
3. Holdout predictions

### Business Problem:
1. What are the most important variables in predicting the selling price of a house?

2. What variables can we create to make a strong model?

3. Is there any difference in price depending on the month of when a house is sold?


### Data
The data set was provided by Flatiron School.

### Results

The model was able to predict houses with a RMSE of 164078.53 and a R-squared score of 0.80. During the construction of the model, it turned out that most of the variables helped predicting house prices. The features with the highest correlations with price were number of bedrooms, number of bathrooms, and square-feet living space. All the continuous variables helped to create a better model. However, categorical variables did not help as much. Zipcodes was an exception.

 It's also interesting to notice that, based on the data, houses sold during hotter months (between March and October) had a higher price than houses sold during colder months. 

### Next Steps

- Use the coordinates to add atributes such as good schools and how close the houses are to big companies and the commercial district.

### Navigation
- 'KingsCountyHousingPrices.ipynb': Notebook containing all the EDA, data visualizations, feature engineering, and models.
- 'housing_preds_ismael_araujo': Notebook predicting house prices.
- 'Predict_holdout.ipynb': Notebook with the predictive model being aplied to the data set without prices
- README.md
- model.pickle file
- model.pkl file
- data: folder with the data frames in .csv
- images: folder containing images
