# ANN-for-fashion-MNIST-dataset
Building an Artificial Neural Network (ANN) in TensorFlow 2.0 for fashion MNIST dataset

2 model created and the accuracy is being compared. 

From the first model, we see that our model makes the accuracy of 87% in test dataset which is approximately similar to the last epoch in training set without any parameter tunings, thanks to the dropout we used which prevent overfitting. The next step will be do to some parameter tuning and see if the model makes good predictions.

From the second model, we see that our model makes the accuracy of 88.15% in test dataset which is almost similar to the last epoch in training set. With adding one hidden layer and increasing the eopch from 5 to 10, the predictions increase by approx 1% in both training and test.

From this two models we can see that with careful parameter tuning, better model can be made. If it was for the production purpose, this model can be further improved by trying different parameters tuning as done in this model.
