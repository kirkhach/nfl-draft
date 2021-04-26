# nfl-draft

## Very rough plan

data:
- standardize data types for each predictor
- dummy variables for categorical
- for NA values: either 0 or mean values of category or eliminate player?
- graphs
    - CarAV by position, CarAV versus all factors, counts of categorical factors, means of numerical factors



analysis:
- linear reg for entire model, offense/defense, by position 
    - approximate value (CAV) as outcome 
- refit dropping factors with low p-values
- normalize features so coefficient values are meaningful
- lasso regression
- classification into groups based on cut off of CAV for labels such as pro-bowl level, starter, bench, bad
- cluster?


Use best model on most recent draft class to predict success
