# DCGN

Deep learning approach for cancer subtype classification using high-dimensional gene expression data
It is built with **Tensorflow ** and **Python 3**.


## Requirements

  * python 3.7, numpy, scipy, TensorFlow 2.4, pysam


## Codes

  * DCGN.ipynb
  * Comparative methods.ipynb


## Data

  * BLCAMDAsmote.mat
  * BLCALundsmote.mat
  * BLCAcitsmote.mat
  * The BRCA dataset is too large, the original dataset can be downloaded from www.acsu.buffalo.edu/~yijunsun/lab/DeepType.html


## Usage

### Data preprocessing

1. Read the data (.mat), check the data and label dimensions,
2. Feature normalization before training
3. Set a random seed and shuffle the dataset

### Build the model

1. Change the shape according to different datasets in the model.build function
2. The last layer of data set BLCALund data set must be greater than 10 nodes.

### Train Model

1. Set the loss function and evaluation indicators
2. Define the training and validation steps
3. Defining and dividing the dataset
4. Perform training and validation steps in a loop
