# Predicting-if-there-will-be-Rainfall-tommorow.
Building a Logistic Regression model to predict if  there will be rainfall tomorrow.

I checked for the missing values and removed columns having a greater share of null values.

I visualised the data to explore insights from and and checking for the correlation among different variables.

I divided the data into train and test set and created dummies for the categorical data.

I used the MinMaxScaler to scale the data to make it easy to interpret our result.

I then visualised for the correlation among the dummy variables created by us.

Using RFE we selected the features and then eliminated the features having high p-value and high VIF manually.

I checked for the accuracy of our model and the created a confusion matrix and checked for the sensitivity and specificity of our model.

I then found the optimal cut-off point which balances the accuracy, sensitivity and specificity of our model.

I then created a ROC curve and checked the area under the ROC curve for our model.

Using our model we predicted on the test data and checked for its accuracy, sensitivity and specificity.
