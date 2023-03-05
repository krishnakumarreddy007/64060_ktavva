# Fundamentals of Machine Learning (MIS 64060):

Assignment 1: 

Purpose
The purpose of this assignment is to set up and use the tools for this course.

This assignment will concentrate on using R and Git. Specifically, you will do the following:
1. Download a dataset from the web. You may use any source, but specify the source in your code. Also ensure that the data has a mix of quantitative and qualitative (categorical) variables.
2. Import the dataset into R
3. Print out descriptive statistics for a selection of quantitative and categorical variables.
4. Transform at least one variable. It doesn't matter what the transformation is.
5. Plot at least one quantitative variable, and one scatterplot
6. Upload your R program, and any associated datafiles to your git account. Remember to create a separate repository for this class.
7. Paste the address to your repository in the assignment submission box here in Canvas.

Learning Outcomes
CLO 4: Know how to use software tools (such as R) effectively to implement machine learning algorithms for data mining/visualization and analytics

Assignment 2:

Purpose
The purpose of this assignment is to use k-NN for classification.

Directions
Universal bank is a young bank growing rapidly in terms of overall customer acquisition. The majority of these customers are liability customers (depositors) with varying sizes of relationship with the bank. The customer base of asset customers (borrowers) is quite small, and the bank is interested in expanding this base rapidly in more loan business. In particular, it wants to explore ways of converting its liability customers to personal loan customers. 
A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise smarter campaigns with better target marketing. The goal is to use k-NN to predict whether a new customer will accept a loan offer. This will serve as the basis for the design of a new campaign. 
The file UniversalBank.csv contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer’s relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign. 
Partition the data into training (60%) and validation (40%) sets. 
Consider the following customer: 
1. Age = 40, Experience = 10, Income = 84, Family = 2, CCAvg = 2, Education_1 = 0, Education_2 = 1, Education_3 = 0, Mortgage = 0, Securities Account = 0, CD Account = 0, Online = 1, and Credit Card = 1. Perform a k-NN classification with all predictors except ID and ZIP code using k = 1. Remember to transform categorical predictors with more than two categories into dummy variables first. Specify the success class as 1 (loan acceptance), and use the default cutoff value of 0.5. How would this customer be classified? 
2. What is a choice of k that balances between overfitting and ignoring the predictor information? 
3. Show the confusion matrix for the validation data that results from using the best k. 
4. Consider the following customer: Age = 40, Experience = 10, Income = 84, Family = 2, CCAvg = 2, Education_1 = 0, Education_2 = 1, Education_3 = 0, Mortgage = 0, Securities Account = 0, CD Account = 0, Online = 1 and Credit Card = 1. Classify the customer using the best k.
5. Repartition the data, this time into training, validation, and test sets (50% : 30% : 20%). Apply the k-NN method with the k chosen above. Compare the confusion matrix of the test set with that of the training and validation sets. Comment on the differences and their reason. 
File Attached: UniversalBank.csv

Learning Outcomes
The assignment will help you with the following course outcomes:
1. Think critically about how to use machine learning algorithms to solve a given business problem.
2. Know how to formulate business problems and identify relevant data to use in modeling frameworks.
3. Know how to evaluate the appropriateness and estimate the performance of using k-NN for a given task.
4. Know how to use software tools (such as R) effectively to implement k-NN.
5. Foster the communication and presentation of statistical results and inferences.
