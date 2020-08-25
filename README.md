# Introduction to Articial Neural Networks (ANN)

There are many types of ANN but the most popular types, which we have used and implemented, are feed-forward neural network, recurrent neural networks (RNN) and convolutional neural networks (CNN).

## Feed-Forward Neural Network 
This is one of the simplest form of ANN, where the input travels only in one direction. The data are passing through input layer and exiting on the output layer. It may have hidden layers or not. As the name suggested, it only has front propagated and not back propagation.

![ffnn](https://github.com/netsatsawat/introduction_to_ANN_tensorflow/blob/master/pic/feedforward_NN.png)

## RNN
Recurrent neural networks are different from traditional feed-forward neural networks. Recurrent neural networks are designed to better handle sequential information. They introduce state variables to store past information, combine with the current inputs to determine the current outputs. Some common examples of RNN are based on text data and time series data.

![rnn](https://github.com/netsatsawat/introduction_to_ANN_tensorflow/blob/master/pic/ff_to_rnn.PNG)

## CNN
CNNs, like neural networks, are made up of neurons with learnable weights and biases. However, they are a powerful family of neural networks that are designed for computer vision. The application of CNNs related to image recognition, object detection, semantic segmentation, etc.

![cnn](https://github.com/netsatsawat/introduction_to_ANN_tensorflow/blob/master/pic/NN_2_CNN_v2.png)

<br>

Please go through the code section for the implementation using TensorFlow v 2.3.0 or [here](https://nbviewer.jupyter.org/github/netsatsawat/introduction_to_ANN_tensorflow/blob/master/code/Introduction%20to%20ANN.ipynb).
