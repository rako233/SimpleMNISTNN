# Simple Neural Network for MNIST data
I made this Jupyter notebook to learn some concepts of Keras.

- Showing the progress of the training in a graph
- Easy configuration of hidden layers
- Normalizing the input data
- Initializing the weights with the Xavier function
- Regularizing the weights with a L2 regularizer
- Plotting accuracy and loss under training
- Using tensorboard to monitor the training
- Using different learning rates while training

The adaptation of the learning rate to the slope of the loss function is paying of. Just compare these examples monitored with tensorboard:

<img src="https://screenshots.firefoxusercontent.com/images/c54c6e62-03c2-4c64-9e7e-91ddeef36604.png"/>

The blue kurves are from the run with a shifting learning rate. It allows to start with a larger learning rate and end with a much smaller learning rate an the end. 

The hyperparameters are optimized for GPU. I installed Anaconda, Cuda9 and Keras on Ubuntu 16.04 to do this experiment.

