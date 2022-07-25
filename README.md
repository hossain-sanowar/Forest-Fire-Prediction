<div id="top">Fire Prediction of Forest Area</div>

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

* Dataset Source: [UCI Repository](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset++#).

# About the Project:

[![Screenshot (10)](web_page.png)
](https://fire-prediction-forest.herokuapp.com/)

[LINK TO HEROKU APP](https://fire-prediction-forest.herokuapp.com/)


The algorithm for Machine Learning is used to anticipate Forest Fires. The dataset is obtained from the UCI data repository. The dataset consists of 244 instances that aggregate data from two Algerian regions: Bejaia in the northeast and Sidi Bel-abbes in the northwest. June through September 2012 are covered by this dataset. This dataset has 11 variables, including Temperature, Relative Humidity, Wind Speed, Rain in millimeters, Fine fuel moisture code, Drought code, Initial spread index, Fire weather index, and fire and non-fire classifications. In this project, the dataset is divided into two groups in order to train machine learning models for classification prediction and regression prediction.

This dataset is placed on the MongoDB server in order to facilitate analysis. After downloading this dataset from the MongoDB server, exploratory data analysis is conducted to determine the number of numerical features, the number of categorical features, the number of missing values, the percentage of outliers, etc. Then, these challenges are solved using NumPy, Pandas, Matplotlib, and Seaborn in order to get clean data for machine learning techniques. Then, the normalize approach is performed to this dataset to create a common data range of 0 to 1 in order to increase the model's efficiency. In the feature selection phase, the correlation approach is used to determine which features are essential and which are not.

After obtaining the final features, the classification machine model is trained based on the most significant characteristics, and the classification model that accurately predicts classes such as fire or no fire in the forest region is chosen. Regression analysis employs a similar procedure, but train characteristics are distinct. In addition, the Cross-validation, RandomizedSearchCV, and GridSearchCV techniques are used to get the optimum model. Based on assessment techniques like as accuracy, precession, recall, F1 score, confusion matrix, mean absolute error, and r2 for this dataset, the best classification model for this project is XGBOOST, while the best regression model is RandomForest Regressor.

In the last phase, a web application is built using the Flask module, HTML, and CSS in order to evaluate the testing results. In addition, the Heroku and Postman apis are used to test the model.

  
**Technology:** Python, Sci-kit learn, Pandas, NumPy, Matplotlib, Seaborn, MongoDB, Flask, Heroku, Postman, HTML, CSS, Git, GitHub, VsCode.

**Classification Machine Learning Algorithms:** XGBOOST, Adaboost, RandomForest, DecisionTreeClassifier, KNeighborsClassifier, Support Vector Machine, Logistic Regression, RandomizedSearchCV, GridSearchCV, and Cross-validation.

**Regression Machine Learning Algorithms:** XGboostRegressor, AdaBoostRegressor, Linear Regression, Lasso Regression, Ridge Regression, ElasticNet, Random Forest Regressor, DecisionTreeRegressor, K-Nearest Neighbour Regressor, Support Vector Regressor, RandomizedSearchCV, and GridSearchCV.

<!--contact-->
[reach_linkedin]: https://www.linkedin.com/in/hossainsanowar/
[reach_gmail]: md.sanowar21@gmail.com

<p align="right">(<a href="#top">Back</a>)</p>
