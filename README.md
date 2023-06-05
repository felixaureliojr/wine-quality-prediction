# Wine Quality Prediction Using Binary Logistic Regression

This project aims to develop a machine learning model that predicts the quality of wines based on their chemical properties. The project utilizes a dataset containing various physicochemical attributes of wines, and employs a data analysis and machine learning pipeline to explore the relationships between the variables and wine quality. Feature selection techniques are applied to identify the most influential features, and a binary logistic regression model is trained and evaluated using performance metrics such as accuracy, precision, recall, and F1-score. The project provides insights into the factors influencing wine quality and offers a practical model for predicting and classifying wine quality based on its chemical composition.

## About the dataset
This datasets is related to red variants of the Portuguese "Vinho Verde" wine. The dataset describes the amount of various chemicals present in wine and their effect on it's quality. The datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

Link to dataset: https://archive.ics.uci.edu/ml/datasets/wine+quality.

## Results and Evaluations
The Wine Quality Prediction project successfully built a logistic regression model to predict the quality of wines based on their chemical properties. The model achieved an accuracy of 76.42% and demonstrated good performance in terms of recall (77.95%), precision (79.2%), and F1-score (78.6%). The evaluation of variable correlation revealed that alcohol content had the strongest positive correlation with wine quality, while volatile acidity exhibited a negative correlation. Feature selection identified pH and residual sugar as having weaker influence on wine quality and were excluded from the model. The model's performance and the identified influential variables provide valuable insights for understanding and predicting wine quality based on its chemical composition.

## Appendix
Compilation of some graphs generated from this project:
![Wine Quality/Wine.png](https://github.com/felixaureliojr/wine-quality-prediction/blob/536adf576ce966272a359c009615fb41bd4f6ffb/Wine%20Quality/Wine.png)
