# Image Classification Project using CIFAR-10 dataset

This is my project submission for the Deep Learning Foundation nano degree by Udacity.

In this project, I classify images from the CIFAR-10 dataset. The dataset consists of airplanes, dogs, cats, and other objects. The dataset was preprocessed, then I train a convolutional neural network on all the samples. I normalize the images, one-hot encode the labels, build a convolutional layer, max pool layer, and fully connected layer. At then end, you'll see their predictions on the sample images.

I use floyd to train the model. More on floyd at https://www.floydhub.com. But you can use AWS or other environments with GPUs to train the model.

## Download CIFAR-10 dataset

You can download the CIFAR-10 dataset if you need. However, running the notebook downloads the CIFAR-10 dataset if it is not available.

`wget -c https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz`
