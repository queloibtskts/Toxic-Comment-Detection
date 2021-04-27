# appliedDataSci_finalProject
This is a group project produced by Xiaoyue Lin, Yuling Zheng and Xiyan Zhang. 

In this project, we aimed to classify toxic comments using Machine Learning models, which can be applied in censoring inappropriate comments on social media platforms. 

The dataset used for training and testing is obtained from Jigsaw Unintended Bias in Toxicity Classification competition on Kaggle: 
https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/data

The models we explore and experiment in this work are Multinomial Naive Bayes, Support Vector Machine, Long Short-Term Memory network and BERT.

We used Accuracy, F1-score and false alarm rate the evalute our models. Overall, LSTM and BERT are the two most effective models for the task with similar accuracy and F1 scores. Furthermore, the evaluation of the classification problem has also performed on comments related to different identities. 

We found that algorithms with different hyperparameter settings performed differently in detecting comments related to different identities (e.g. disabled, black or female). In practice, we suggested that the choice of the best model could depend on the users demographics and the level of censorship of a social media platform.
