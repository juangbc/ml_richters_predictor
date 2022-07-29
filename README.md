# ml_richters_predictor

## Richter's Predictor: Modelling Earthquake Damage

This repository addresses  trying to predict the ordinal variable damage_grade, 
which represents a level of damage to the building that was hit by the earthquake. 
There are 3 grades of the damage:

* 1 represents low damage
* 2 represents a medium amount of damage
* 3 represents almost complete destruction

We attempted to get a best prediction for the given data set. To do this we followed these steps:
1. Category encoding (using two encoding systems, target encoder and dummy encoder)
2. Linear regression to check p values and do some feature selection
3. Grid search to tune hyperparameters
4. Predictions with GradientBoostingClassifier, XGBClassifier, Random forest