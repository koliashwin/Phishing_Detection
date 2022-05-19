# Phishing_Detection

We have to predict whether the website is legitimate or a phishing. i.e. the resulting output will contain 2 categorical values [1,-1] where 1 represents legitimate and -1 represents phishing.

So to make predictions will use logistic regression, Decision Tree Classifier and Random Forest Classifier

For the final output will consider the model with highest accuracy.


approach:

  Step 1 : import required libraries and read the data form training dataset

  Step 2 : check for the data impurities(there where none for this data set)

  Step 3 : split the dependent and independent variables

  Step 4 : split the dataset into train and test set, now data is ready to use 

  Step 5 : fit the data into the Logistic Regression model and calculate the accuracy

  Step 6 : repeat Step 5 for Decision Tree Classifier model and Random Forest Classifier
  model

  Step 7 : now we have the accuracy scores from 3 models

  Step 8 : choose model with the highest accuracy and make predictions for given test files

  Step 9 : finally write the data into csv file 

