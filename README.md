# deep-learning-challenge.


# The report should contain the following:

# Overview of the analysis: Explain the purpose of this analysis.

# Results: Using bulleted lists and images to support your answers, address the following questions:

# Data Preprocessing

1. What variable(s) are the target(s) for your model?

**Answers** The target variable is  "IS-Successful" column

2. What variable(s) are the features for your model?

**Answers** The features for model are :

APPLICATION_TYPE,	AFFILIATION	,CLASSIFICATION,	USE_CASE, ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS,	ASK_AMT

3. What variable(s) should be removed from the input data because they are neither targets nor features?

**Answers** EIN(Employee Identification Number), Name

# Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?

**Answers** For this model 3 hidden layers each with many neurons because the compute seems to increase the accuracy above 75%. This is expensive . The first activation is "relu" and other layers are "sigmoid". It might boost the accuracy using the functions. Readusting my data that names as get dummies can factor in with better scores.


2. Were you able to achieve the target model performance?

yes

3. What steps did you take in your attempts to increase model performance?
converting the "Name" column in to data points which has the biggest impact on improving efficiency but costly and it requires adding the third layer using "sigmoid" activation function.

# Summary: Summarize the overall results of the deep learning model.
Overall the accuracy is above 75 %. An applicant has a 78% chance of being successful if they follow the below guidelines:

Name of applicants appear more than 5 times.
Type of application following T3, T4, T5, T6, T7, T8, T10, T19 
application of following classification 



 #Include a recommendation for how a different model could solve this classification problem, 
#and then explain your recommendation.

Random Forest Model
