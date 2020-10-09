# Deep Learning Image Classifier (Sports) 

Code Written in Python using Jupyter Notebook. Open the notebook [here](https://github.com/sshreyas999/Sports-Classifier-Deep-Learning/blob/main/Sports%20Classifier%20(CNN%20%2B%20Transfer%20Learning).ipynb) for code and thorough analysis.

**Note**: Training/Validation data set not hosted on github, can be downloaded from [here](http://vision.stanford.edu/lijiali/event_dataset/).

## Objective  
In this notebook, we aim to build a deep learning model which will classify images according to what sport is being played in them. We have 8 different types of sports - Badminton, Bocce, Croquet, Polo, Rock Climbing, Rowing, Sailing, and Snowboarding.

We will build two models to see which one performs better-  
1. **CNN with the basic architecture** - Conv2D layers, Max Pooling Layers, followed by Dense Layers.
2. **CNN with Transfer Learning** - Weights from a pre-trained model, followed by a Dense Layer for our problem.

## Dataset
There are two datasets:
1. The training dataset contains 1579 divided into 8 folder (classes). Take 80% of the data for training, the other 20% will serve as a validation set.
2. The test dataset is manually created using images from the web to specifically test this model. It has 16 images and can be found in this repository.
## Outline  
The following procedures are carried out in the notebook:
### Visualize Training Data  
Take a look at images and true labels. Get a feel for the quality of the dataset.
### Model Fitting & Evaluation (Approach 1)
Fit the model using **basic CNN architecture**, analyze metrics and draw conclusions.
### Model Fitting & Evaluation (Approach 2)  
Fit the model using basic **transfer learning**, analyze metrics and draw conclusions. 
### Predicting on Test Dataset
Pring out every image in the test dataset, along with their true and predicted labels.

## Conclusion
The Basic CNN model had a **74.3%** validation accuracy, while the transfer learning model had a **97.5%** validation accuracy. The transfer learning model got all 16 predictions right (**100%** accuracy) on the test dataset.
