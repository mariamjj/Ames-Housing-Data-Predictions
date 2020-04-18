# Ames Housing Data Predictions

Mariam Javed, DSI-TOR

### Overview

In this project, we will evaluate the performance and predictive power of a model that has been trained and tested on data collected from homes in suburbs of Ames, Iowa. A model trained on this data that is seen as a good fit could then be used to make certain predictions about a home — in particular, its monetary value. This model would prove to be invaluable for someone like a real estate agent who could make use of such information on a daily basis.

The Ames housing data has 879 entries that represent aggregated data for 80 features for homes from various suburbs in Ames, Iowa from 2006 to 2010. The data dictionary for this dataset can be found online [here](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt).

---

### Problem Statement

We are interested in evaluating the price of a house on sale in Ames, IA by using a regression model on the Ames Housing Dataset and: i) predicting what the sale price will be and ii) determining what variables (if any) effect the final sale price.

---

### Executive Summary

This project predicted the sale price of homes in Ames, Iowa using a Linear Regression (LR) model - a Lasso Regression, Ridge Regression, Elastic Net Regression, and KNN Regression model were all implemented, however, the LR performed the best. Our model returned the highest and most consistent R^2 terms (0.885 and 0.875 for the train test and validation test set respectively) with a RMSE of: 28040.57.

Some of the variables that increase the value of a house in Ames, Iowa iare the total square feet of the house, house age, type of house, size of the garage, basement condition/square feet, and finally, the overally quality of the house. Alternatively, miscellenaous feautures (elevators, sheds etc.), utility information, pool quality (if it exists), and low quality finished square feet are among some of the features that devalue a house. Home owners or prospective home buyers should consider improving the basement size and quality of the house, if possible, to help increase the value of the house as this has shown to have a significant impact. 

It's also of interest to note that homes in the 'StoneBr', 'NridgHt', and 'NoRidge' neighborhoods have the highest overall value in contrast to homes in the 'MeadowV' and 'IDOTRR' neighborhoods in Ames, Iowa.

For homeowners looking to buy houses in other Cities or States, I believe this model will be able to generalize enough to make accurate predictions for sale prices elsewhere. In real estate, the same features and variables are used to buy and sell homes, for this reason, this model should be easily able to adapt once a few names and functions are adjusted.

Happy Home-Buying! 

### Contents:
- [EDA and Cleaning](#EDA-and-Cleaning)
- [Exploratory Visualizations and Analysis](#Exploratory-Visualizations-and-Analysis)
- [Feature Engineering](#Feature-Engineering)
- [Model on Training and Validation Test Set](#Model-on-Training-and-Validation-Test-Set)
- [Test Model!](#Test-Model)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

---