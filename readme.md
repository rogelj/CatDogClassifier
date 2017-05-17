# A cat and dog image classifier

This repo uses TensorFlow to retrain the [Inception](https://github.com/tensorflow/models/tree/master/inception) Convolutional Neural Net (CNN) trained on [ImageNet](http://www.image-net.org).

Here we are retraining the last layer of the CNN to classify images of cats and dogs. The data set used comes from the [Dogs v Cats Kaggle competition](https://www.kaggle.com/c/dogs-vs-cats).

You will need an appropriate installation of TensorFlow. You are also recommended to take a look at this [TensorFlow repo in GitHub](https://github.com/tensorflow/tensorflow). 

## Steps

1. Download the data from the [Dogs v Cats Kaggle competition](https://www.kaggle.com/c/dogs-vs-cats). You will need to move the cat pictures to a folder called `.\data\cats` and the dog ones to a folder called `.\data\dogs`
2. You may also want to partition the data set into a 80/70% training and 20/30% testing. 
3. Open the Jupyter notebook provided and follow the steps there. 

Et voilà, you can tell a cat from a dog!
