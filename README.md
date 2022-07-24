# Credit_Risk_Analysis

## Overview
-The purpose of this analysis was to find the best model to predict the loan status of different customers based off of different target groups. The models used in this analysis were undersampling, oversampling, combination (over and under), balanced forest, and adaboost.
## Results
-For the first metric, recall, I found that the Adaboost model had the highest score at 0.94 average. For the second metric, percision, I found that all models scored a 0.99 average. For the third metric, F-score, the adaboost model had the highest score at 0.97, with the random trees model coming in at a close second, at 0.95. From this analysis, we can conclude that the adaboost model is the best fit for this dataset, with the random trees model being a close contender. Included are the screenshots of the predictive tables.
-![Regular Oversampling Predictive Table]('Resources/1_Regular_oversampling')
-![Smote Oversampling Predictive Table]('Resources/2_Smote_oversampling')
-![Undersampling Predictive Table](Resources/3_undersampling)
-![Combination Predictive Table](Resources/4_Combination)
-![Balanced Random Forest Predictive Table](Resources/5_Balanced_Random_Forest)
-![Adaboost Predictive Table](Resources/6_Adaboost)


## Summary
-To use the best model for the loan predictions, I ran several models and compared their percision, recall, and F-score. I found that the best model to fit the data was the adaboost model. 