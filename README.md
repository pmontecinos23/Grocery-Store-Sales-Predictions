# Grocery-Store-Sales-Predictions

## Outlet sales predictions using regression models

**Author: Paul Montecinos**

### Business problem:
 * Determine best model to predict sales
 
### Data:
 * https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/ 

## Methods
 * Cleaned and filled data using ordinal coding, fequent method, and median.
 * Processed cleaned data using sklearn imports
 * Once data was cleaned preprocesses fit data to models
 
 ## Exploratory Data Visuals/results
 ![Sales pred](https://user-images.githubusercontent.com/29460152/224519094-6ed8acf1-115b-472d-9f5b-a041609ec416.png)
 
  * The barplot above indicates supermarkets type 1 and 3 generate the most sales
  * The common size between the most generated stores would be the medium size outlet

 ![Sales pred1](https://user-images.githubusercontent.com/29460152/224519256-8fa49873-c19b-4ebe-a6c1-da5f237949b2.png)
 
  * The lineabove indicates higher visibility doesn't equate to outlet sales
  * MRP does seem to have a correlation with outlet sales
 
 ## Decision Tree Model
  * RMSE is the average squared amount, expressed in the same units while punishing larger errors. Making RMSE easier to interpret
  * R^2 is a percentage of the variation in the target variable that a model can explain by using all the features together
  
  * Training Scores 
     * RMSE (Root Mean Squared Error): $1082.66
     * R^2 (Root Squared Score): 0.604
  * Test Scores
     * RMSE (Root Mean Squared Error): $1057.45
     * R^2 (Root Squared Score): 0.595
  
  * The RMSE score shows that our model can predict sales within $1057.45 of the target
  * The R^2 score shows we can explain 59% of the variation in the target

 ## Recommendations
  * Recommend more tuning, models and DATA

 ## Limitations
  * The amount of data

 ## Next Steps
  * Obtain more data and run additional models
  
 ## For further information
  * For any additional questions, please contact Paul at paul_montecinos23@gmail.com
 

  



