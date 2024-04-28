# Milk_Quality_Prediction
The machine learning model developed aims to estimate the quality of milk using various features extracted from the dataset. The dataset consists of a set of milk samples, with each sample represented by several parameters: pH, temperature, taste, odor, fat content, turbidity, and color. The target variable, or the label, is the grade of the milk, which is categorized as high, medium, or low. This is a classification model.

# Steps 
1. Importing the dataset, 2. Data Preprocessing, 3. Data Visualisation,
4. Feature Selection, 5. Model Selection, 6.Training and Testing the model,
7. Evaluating the model

# Dataset 
https://www.kaggle.com/datasets/cpluzshrijayan/milkquality

# Models
1. Gaussian Naive bayes
2. Decision Tree

# Evaluation of Model
When gaussian naive bayes model is used for classification, the model is tested and evaluated using classification report and confusion matrix. By using non scaled features for training and testing the model, we get the accuracy as 0.92138. By using the scaled features for training and testing the model, we get the accuracy as 0.9496.
In this ML model when we have used a decision tree as this is a classification model and as it consists of both numerical and categorical data. By using the non-scaled features for training and testing, we have a built decision tree which has criterion as Gini index and depth as 10. The accuracy of the model is 0.98742. By using the scaled features for training and testing, we have a built decision tree which has criterion as Gini index and depth as 10. The accuracy of the model is 0.9905. When we change the criterion to entropy and maximum depth is 9, we get the accuracy as 0.98742. When
we change the criterion to log loss and maximum depth is 9, we get the accuracy as 0.98742.Therefore, we get the ideal value of maximum depth as 9.
By evaluating both the models of Naive Bayes and Decision tree, we have found out that Decision tree is the best fit model for this data frame. Also, Naive Bayes is often preferred when dealing with high-dimensional data with few training examples, but Decision Trees are often preferred when dealing with complex data structures, where the model’s ability to handle both categorical and continuous data and its ease of interpretation make it an ideal choice.
