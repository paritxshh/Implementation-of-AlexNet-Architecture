# Implementation-of-AlexNet-Architecture
# AlexNet 
AlexNet is a deep convolutional neural network that achieved state-of-the-art results in the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) 2012. This repository contains a PyTorch implementation of AlexNet that can be trained on various image classification datasets.

# Features
1. Eight-layer architecture, including five convolutional layers and three fully connected layers
2. Uses ReLU activation functions and max pooling to reduce the spatial size of feature maps
3. Employs local response normalization to enhance the contrast between different features
4. Data augmentation and dropout regularization to prevent overfitting
5. Input images resized to 227x227 pixels
6. Trained on large datasets of labeled images, such as ImageNet or CIFAR-10

# Usage
To train AlexNet on your own dataset, follow these steps:

1. Clone this repository
2. Install PyTorch and other required dependencies
3. Prepare your dataset, ensuring that the images are resized to 227x227 pixels and organized in folders by class
4. Modify the training script to point to your dataset and adjust hyperparameters as needed
5. Run the training script and monitor the training progress
6. Evaluate the trained model on a validation set or test set

# References
1. Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). ImageNet Classification with Deep Convolutional Neural Networks. Advances in Neural Information Processing Systems (NIPS), 1097-1105.
2. PyTorch documentation
