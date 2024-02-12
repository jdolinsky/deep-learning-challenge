# Overview 
In this project I had to create a ML model to predict if the applicants that will be funded by a Charitable organization called Alphabet Soup will be successful. For this analysis we had a dataset containing various measures on 34,000 organizations that have been funded by Alphabet Soup. 

This project compromised of the following 3 steps:

* Preprocessing the data for the neural network
* Compile, Train and Evaluate the Model
* Optimizing the model

# Data Processing
The target variable for this dataset was 'IS_SUCCESSFUL'. 
For the features I dropped 'EIN' and 'NAME' columns as they seemed non-beneficial for our model. I later dropped 'STATUS' and 'SPECIAL_CONSIDERATIONS' columns as a part of the optimization, but it did not have any significant impact on the accuracy of the predictions.

I started training the model with initial 5 and 8 nodes in two layers. During the optimization I increased those values to 20 for each layer. That did not give me a desired 75% accuracy. The highest I got in this experiment was ~72.9% accuracy. 

# Technology 
Pandas, TensorFlow, Machine Learning, Google Collab