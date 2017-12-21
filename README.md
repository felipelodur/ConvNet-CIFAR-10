# Image-Classification-CIFAR-10
Project developed as coursework for Udacity "Deep Learning Fundamentals" Nanodegree. This project consits of implementing a **convolutional neural network** to classify a image dataset.
**Tensorflow** was used to apply the deep learning model.

## CIFAR-10 dataset
In this project, I classified images from the CIFAR-10 dataset.
The dataset consists of airplanes, dogs, cats, and other objects. 
The dataset was preprocessed to fit the model and improve performance.

## Classifier
In order to classify, a **convolutional neural** network was used.
In the training, the images were *normalized* and *one-hot encode* labels were used.
The convolutional network here implemented can be divided in the following layers:
- Convolutional Layer
- Max Pool Layer
- Fully Connected Layer

## Results
The project meets the specifications provided by Udacity, as follows:
- All the unit tests in project have passed.
- The *normalize* function normalizes image data in the range of 0 to 1, inclusive.
- The *one_hot_encode* function encodes labels to one-hot encodings.
- The conv2d_maxpool function applies convolution and max pooling to a layer.
- The flatten function flattens a tensor without affecting the batch size.
- The fully_conn function creates a fully connected layer with a nonlinear activation.
- The output function creates an output layer with a linear activation.
- The conv_net function creates a convolutional model and returns the logits. Dropout should be applied to alt least one layer.
- The train_neural_network function optimizes the neural network.
- The print_stats function prints loss and validation accuracy.
- The hyperparameters have been set to reasonable numbers.
- The neural network validation and test accuracy are similar. Their accuracies are greater than 50%.












