# Breast Cancer Prediction using Feedforward Neural Network


# SUMMARY

This project is to create a deep learning model using feed forward neural network by predicting if the breast cancer tumour is malignant or benign. The dataset is obtain from https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

A correlation matrix map is plotted to evaluate which features contributes the most on the diagnosis of the tumour. From this matrix, it is concluded that the mean radius, mean perimeter, mean area, mean texture, mean compactness, mean concavity and mean concave points of the tumour weighs the most in this analysis.

<img width="894" alt="Screenshot 2022-04-29 at 00 11 24" src="https://user-images.githubusercontent.com/58509210/165797418-ab0cf6a5-4ce1-4156-bf19-980cf8ec7220.png">

The model is built with 1 input layer, 3 hidden layers, 1 dropout layer, and 1 output layer. 

<img width="261" alt="Screenshot 2022-04-29 at 00 20 02" src="https://user-images.githubusercontent.com/58509210/165798955-9c668ff1-0705-4203-8979-6157179daad8.png">

The model is trained using 100 epochs with a batch size of 32. An early stopping is added and the model stopped at epoch 6.

From the results obtained, the model has an accuracy of 95% with a loss of only 0.1. This shows that the model is well trained and has the best accuracy to predict whether the tumour is malignant or benign.

<img width="1045" alt="Screenshot 2022-04-29 at 00 25 21" src="https://user-images.githubusercontent.com/58509210/165799705-ac603b41-113f-46e2-a33d-4f87db5d2b9a.png">

From this prediction analysis, only 4 predictions are incorrect while the rest are correct. This shows that our model is extremely well trained. 

<img width="367" alt="Screenshot 2022-04-29 at 00 27 48" src="https://user-images.githubusercontent.com/58509210/165800402-149f866d-6731-43b8-b913-a437da9f8ea9.png">
