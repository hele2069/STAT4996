# STAT4996
Capstone Project - Predicting AOM Level in Seawater

### Introduction
Methane is an important energy source for sea-floor life, and we are interested in understanding how the micro-organisms convert it into other compounds. One of the mechanisms for this conversion is called anaerobic oxidation of methane (AOM). Measurements and equipment for measuring AOM are relatively expensive, and therefore our goal is to predict AOM using statistics.
This data set is collected from soil samples from the floor of the Gulf of Mexico. There are a total of 275 observations.

### Proposed Approach
After exploring our data set, we found extreme variations among the variables, including substantial outliers. There are a few observations where AOM level exceeds thousands, where the majority has a value of less than 100. Therefore, we hope to first explore the existence of AOM by converting AOM level into ‘Yes’ and ‘No’ indicating its presence. Then, using the best model we find, we will subset our data set to those being predicted as containing AOM existence. Then, we hope to fit another model that best predicts the actual level of AOM. In other words, we first try and fit a classification model, then use it to subset our data and fit it into a regression model.
We would also want to note that our main goal is prediction, not interpretation. Therefore, the relationships between predictors and the response variable become less important. Our two most important metrics are: prediction accuracy for classification, and prediction MSE for regression.
