# Recognizing-Hand-Written-Digits
Setting up a two layer neural network to recognize hand-written digits. Dataset considered was MNIST dataset that consists of 50,000 hand-written digits in the training dataset and 10,000 hand-written digits in the test dataset. A two-layer neural network with rectified linear unit activations was constructed and to evaluate the predicted result, the cross-entropy loss (softmax plus negative log-likelihood) was used. Implemented the neural network using PyTorch.

Similarly, Convolution Neural Networks with two convolutional layers and one fully-connected layer in PyTorch was implemented.

The test accuracy using Feedforward neural network was 96.7% and using CNN was 97.9%. Clearly CNN was giving better accuracy. 

The number of parameters in the feedforward neural network were: 101,770

The number of parameters in CNN were: 8,490

Feed forward NN:(784X128)+(128X10)+(1X128)+(1X10) = 101,770

In a CNN for a conv layer: ((m * n * d)+1)* k), for a pool layer: 0, for a FC layer: (c * p)+1 * c

CNN: ((5* 5* 1)+1)* 10 + ((5* 5* 10)+1)* 20 + (20* 4* 4* 10)+ (1*10) = 8,490

CNN was parameter efficient. 

