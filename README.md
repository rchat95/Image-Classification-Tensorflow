# Image-Classification-Tensorflow
A convolutional neural network trained to classify pictures of some common objects

Dataset used - CIFAR10

60000, 32x32 color images with 10 class labels - airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck. There are 6000 images per class

Built a CNN model class using tensorflow and keras. There is also a function to load or import an existing model, like the VGG16 or the VGG19 model.

Using the CNN model with my own layers, I got an accuracy of 71%. You can play with a lot of parameters such as loss functions, momentum and optimizers.

![Predictions on the CIFAR10 dataset](/output.png)

This model can also be easily applied on a variety of larger datasets.
