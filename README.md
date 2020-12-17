# classification-which-fruit-is-it
The goal is to identify fruit based on the following attributes: mass, width, height and color. The data set is available here:

https://raw.githubusercontent.com/lkyin/ECS189L/main/fruits.csv

Specifically, your goal is to:

## 1. Build a logistic regression classifier to predict the fruit_name variable in terms of the predictors mass, width, height, and color_score. Make sure the model is:
* the best one you can get (based on area under the ROC), and
* is not overfitted (use cross validation).

#### What to report: a) the model coefficients, b) confusion matrix, and c) the area under ROC of your best model.

## 2. Here, build a decision tree classifier to predict the fruit_name variable in terms of the predictors mass, width, height, and color_score. Make sure the model is:
* the best one you can get (based on accuracy on test data),
* is not overfitted (use cross validation).

#### What to report: a) plot of the decision tree and b) the accuracy of your best model on the test data.

## 3. Draw the decision boundaries for each of the 6 possible two-predictor models derived from the models above (6 for the logistic regression and 6 for the decision tree) and consider their performance vis-a-vis the decision boundaries.

#### What to report: Answer the following question in a textbox. What do you notice in terms of the relationship between model performance and decision boundary for each model? 
