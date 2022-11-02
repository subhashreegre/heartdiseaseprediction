# heartdiseaseprediction
This is a machine learning model which can predict the heart disease of a person based on data given.
I have collected the data from kaggle dataset repositories. This .csv file of data contains several health parameters which corresponds to a person's healthiness of a heart.
So after collecting a data my workflow was :
Data Processing:
We can not feed raw data into our machine learning algorithm. So I processed data using pandas dataframe.
after that I splitted data into two types i.e. Training Data and Test Data. This step is known as train test split. We train our machine learning algorithm with train data and 
we will evaluate our model and we will evaluate the performance of our model using Test Data. 

After splitting we will focus on LogisticRegression Model. NOW WHY LOGISTIC REGRESSION MODEL?
 this particular use case is binary classification with an answer of either YES or NO. We are going to classify whether a person has a diseased heart or not. 
 
 After Logistic Regression we need to train the model. That is why we feed more data to the model and check if it is working or not. 
 
 I successfully make a model with 82%(approx.) accuracy of test data and 85%(approx.) accuracy of training data.
