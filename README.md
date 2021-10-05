# Cascade-Cup-Data-Science-Hackathon (My Approach)

### Problem Statement:
In this world of big data, Trell wants us to use the data to predict the age group of their users based on their activity on social media activities.  This will help them to divide their huge userbase and cater differently to each of them. Given this huge dataset, predict the age group of the users, the evaluation metric for the competition is the Weighted F1 score. The Machine learning model we develop will help Trell provide better experience to their users by giving them a better user age specific content which people might find more relatable.

### Dataset Descipion:

Dataset: [Dataset link](https://dphi.tech/challenges/cascade-cup-data-science-hackathon/46/data)

It has 25 independent features and 1 target variable. The target has muliple target classes(4 different categories). The details of each of the fearures can be found in the above link.

### Method:

Done EDA on dataset. One-hot encoded the categorical variables. Selected top 10 features after co-relating them with target variable. 
Applied Linear regression, SVM regression and ensemble algorithms for prediction. GradientBoostingClassifier performed best and was chosen for final submission.

### Results:

Metric for evaluation: F1 score
Training f1-score: 87%
Test f1-score: 78.5%
