# Practicing Transfer Learning in Keras and Tensorflow

## Software Configuration

- GPU usage: Yes
- Tensorflow version: 1.14.0
- CUDA version: 10.0
- cuDNN version: 7.4.2

## Datasets to be Used

You can find datasets for image recognition in [Kaggle](https://www.kaggle.com) and [Tensorflow Dataset](https://www.tensorflow.org/datasets). To learn how to import and manipulate datasets through Tensorflow, see [this document](https://www.tensorflow.org/datasets/overview).

1. [Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data): binary classification (2 classes).
1. [MNIST](http://yann.lecun.com/exdb/mnist/): Multiple classification (more than 2 classes).

## Pre-trained Models to be Used

We can use any pre-trained models contained in [tf.keras.applications](https://www.tensorflow.org/api_docs/python/tf/keras/applications).

1. [MobileNetV2](https://www.tensorflow.org/api_docs/python/tf/keras/applications/MobileNetV2)
1. [ResNet50](https://www.tensorflow.org/api_docs/python/tf/keras/applications/ResNet50)