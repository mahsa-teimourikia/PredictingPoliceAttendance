# Predicting Police Attendance on Road Accidents
The goal of this report is to build a model that predicts if a police officer is likely to attend an accident or not using the accidents dataset provided at: https://data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data


## The Approach (Algorithms and Tools)
I mainly used the standard Python libraries: Numpy and Pandas for data analysis, Scikit-Learn for machine learning, and Seaborn and Matplotlib for data visualizations.

I started by looking at the data and ran some exploratory data analysis to understand the features and their relationships with eachother and with the target. At the next step, I preprocessed, cleaned and prepared the data for being used in fitting the models.

To choose a model, first considering that it was a classification problem I took a look on the classification models (Linear SVC, KNN Classifier, SVC, Random Forests, and AdaBoost). I started with the simplest model (Linear SVC) considering that there have been considerable amount of data and features to train. As the results of the Linear SVC were not satisfying (also after trying the Balanced Sampling and the GridSearchCV to tune the model), I moved to the next model on my list which was the KNN classifier. KNN Classifier provided better precision and recal.

The results are shared on a Jupyter Notebook. Feel free to fork it and also let me know if you are able to implement any approaches which improves the results.
