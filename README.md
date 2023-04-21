<ins>**Building a CNN architecture using the CIFAR10 dataset using Keras Hypertuner**</ins>
In this project, we will build a Convolutional Neural Network (CNN) architecture using the CIFAR10 dataset and Keras Hypertuner. The goal of this project is to find the best hyperparameters for the CNN model that will achieve the highest accuracy on the CIFAR10 dataset.

The CIFAR10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images.

<ins>Installation<ins/>
Before getting started, make sure you have the following packages installed:

tensorflow
keras
kerastuner
If you don't have these packages installed, you can install them using pip:

<ins>Copy code</ins>
pip install tensorflow, keras, kerastuner
  
<ins>Tasks involved</ins>
*Load the CIFAR10 dataset using Keras.
*Preprocess the data.
*Define the CNN model function that takes hyperparameters as input.
*Define the tuner and start the hyperparameter search.
*Print the best hyperparameters and retrain the model using those hyperparameters.
*Evaluate the model on the test set.
*Conclusion
  
This project demonstrates how to use Keras Hypertuner to find the best hyperparameters for a CNN model trained on the CIFAR10 dataset. By finding the best hyperparameters, we can achieve higher accuracy on the test set and improve the performance of our model.
