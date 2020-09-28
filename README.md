# Facebook-Friend-Recommendation
To recommend the users by predicting the missing links.

## Description:
Today one of the most important reason for the growth of the social networking is recommendation of new users. On the basis of this idea, the task is to predict the unknown links for recommending the users. Given, the directed social graph (Data) various graph based measures are used to derive the features from the graph and creating a featurized data to make the machine learning model to predict the unknown links.

### Dataset link : https://www.kaggle.com/c/FacebookRecruiting

## Metrics:
F1-Score, Confusion Matrix

## Results:
Evaluation on Test data

| Model | Precision | Recall | F1-Score |
| ------| --------- | --------| ---------|
| RF | 0.973 | 0.880 | 0.92416 |
| GBDT | 0.986 | 0.870 | 0.92462 |

## Contains 3 files:
1) EDA.ipynb - Exploratory Data Analysis on the Directed Social Graph.
2) Featurization.ipynb - Featurization of Social Graph.
3) Models.ipynb - Modelling
