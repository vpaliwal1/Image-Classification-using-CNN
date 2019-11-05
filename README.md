# Image-Classification-using-CNN

In this project, we will be deploying a convolutional neural network (CNN) for object recognition. This convolutional neural network obtained state-of-the-art performance at object recognition on the CIFAR-10 image dataset in 2015. I will build this model using Keras, a high-level neural network application programming interface (API) that supports both Theano and Tensorflow backends. You can use either backend; however, I will be using Theano.

In this project, we will learn to:

1. Import datasets from Keras
2. Use one-hot vectors for categorical labels
3. Addlayers to a Keras model
4. Load pre-trained weights
5. Make predictions using a trained Keras model

The dataset we will be using is the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes (airplace, dog, cat, bird etc), with 6000 images per class. There are 50000 training images and 10000 test images.

I used the paper, "Striving For Simplicity: The All Convolutional Net" as reference. This paper can be found at the following link:

https://arxiv.org/pdf/1412.6806.pdf

I also used the availabe weights from Github for this project which trained my model fast in comparison to without weights.
