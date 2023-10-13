# CIFAR-10 Image Classification: Machine Learning and Deep Learning
This project involves end-to-end data processing for CIFAR-10 image classification, optimization of both Machine Learning (ML) and Convolutional Neural Network (CNN) models, including fine-tuning individual layers in CNNs.

## Part 1 – Data Processing 

The original [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) contains 60,000 32x32 color images across 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images.

### Tasks:
1. Download the black and white source files [here](https://drive.google.com/drive/folders/1Df7euj71zGxIlpCM8DXmYvhu3dptkw9L).
2. Performed Exploratory Data Analysis (EDA) and discussed the input data.
3. Conducted data normalization.
4. Cerived black and white images from the original color images (tar.gz file). 

## Part 2 – Machine Learning with Logistic Regression and One-vs-Rest Classifier

I have implemented Machine Learning models to classify the input datasets, calculated performance metrics, and documented the work in a Jupyter notebook. Models used are Logistic Regression and One-vs-Rest Classifier
For the better model, I have utilized Grid Search CV to determine the optimum set of hyperparameters.

## Part 3 – Deep Learning

I have created a Convolutional Neural Network (CNN) to classify the input dataset, calculated performance metrics, and documented the work in a Jupyter notebook.

### Optimization Techniques:
- Explored data augmentation,fine-tuned hyperparameters, such as the fine tuning each layer of the model such as Convolutional layer, max pooling, denser layer.
### Performance Analysis:
1. I have concluded the performance of the final model.
2. I have analyzed the effect of input data on performance.
   - Created a new model based on the final model and adjusted it to accept inputs of color images (3 channels).
   - Trained it using the original CIFAR-10 color training images.
   - Calculated the performance using CIFAR-10 color test images.
   - Explained all model performances
