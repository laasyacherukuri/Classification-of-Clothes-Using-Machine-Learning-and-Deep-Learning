# Classification of Clothes using Machine Learning
**This is a project done under the course of Machine Learning Specialization in Cloudxlab.** 
<br/><br/>
Now coming to the project description,
<br/><br/>
Fashion-MNIST is a dataset of Zalando's fashion article images —consisting of a training set of 60,000 examples and a test set of 10,000 examples.
<br/>
1. This is a project based on SUPERVISED LEARNING on Linear Model.
2. I have used different regression algorithms and classifiers on given dataset to compare the prediction accuracy and achieved an accuracy of 87.63% using XGBClassifier.
3. After deciding the final model I used dimensionality reduction to reduce the number of features in the dataset, so that the time taken for grid search and prediction is reduced. Also, I have calculated the scores based on the reduced features.(Used PCA algorithm.)
4. Grid-search is used to find the optimal hyperparameters of a model which results in the most 'accurate' predictions.
5. Thus, evaluated my selected XGBoost model, using best parameters, on the test dataset.
<br/><br/>
The class labels for Fashion MNIST are:
<br/>
Label &nbsp;&nbsp;&nbsp;&nbsp;  Description
<br/>
0    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    T-shirt/top
<br/>
1    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     Trouser
<br/>
2      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   Pullover
<br/>
3    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     Dress
<br/>
4   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      Coat
<br/>
5    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     Sandal
<br/>
6    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     Shirt
<br/>
7     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    Sneaker
<br/>
8    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     Bag
<br/>
9      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   Ankle boot


### Libraries :
```
1. os
2. gzip
3. pandas
4. numpy
5. matplotlib.pyplot
6. sklearn.preprocessing
   -StandardScaler
7. sklearn.metrics
   -accuracy_score
   -precision_score
   -recall_score
   -f1_score
8. sklearn.linear_model
   -SGDClassifier
   -LogisticRegression
10. sklearn.tree
   -DecisionTreeClassifier
11. sklearn.ensemble
    -RandomForestClassifier
    -VotingClassifier
12. xgboost
    -XGBClassifier
13. sklearn.model_selection
    -cross_val_score
    -cross_val_predict
14. sklearn.metrics
    -confusion_matrix
    -roc_curve
    -roc_auc_score
```
