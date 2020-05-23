This example consist of my approach of performing spam classification using Spark MLlib.

For pre-processong data, I have used custom functions and created udfs so that it can be used in spark for distributed processing.

For traning the model, I have used Spark MLlib's classifiers.

For evaluation, I have used MulticlassEvaluator class to find the accuracy of the model.
