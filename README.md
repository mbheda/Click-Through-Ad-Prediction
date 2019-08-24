# Click-Through-Ad-Prediction

This report discusses the project done for Data Analytics course. In
this project, we take the Avito's ad click prediction problem hosted
on Kaggle and develop models to predict whether a user clicks
on the ad, given a set of features. We first start with merging the
relational databases into one table of features. Then move onto to
the data preparation phase, where a bulk of entries are removed
due to noisy information. In the next step, we explore the data and
draw interesting insights from the data. We then move on to the
model building step, where we explore classification algorithms like
Logistic Regression and ensemble classifiers like Random Forest to
model the training data. We also use techniques like grid search
to tune model hyperparameters and cross-validation to improve
model performance. In the final step, we evaluate our models using
various metrics and compare the performance. We can achieve a
maximum of 0.72 recall with XGBoost model. For the extra credits
section, we perform some interesting analytics on Russian textual
data and use the genetic algorithm to get the features that most
affect the classification.
