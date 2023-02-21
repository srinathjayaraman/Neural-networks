# Neural-networks

This repository contains code used to build an image classifier using Convolutional Neural Networks (CNN's). For this I used the CIFAR10 dataset (pronounced "seefar ten") consisting of 50,000 training images and 10,000 test images. I took 10,000 images from the training set to form a validation set and in order to visualise sample images. A modified CNN known as a U-Net was also deployed for the purposes of object detection on remote sensing data (ie. satellite imagery). Object detection is used to classify roads, rivers, buildings, etc. from satellite images. The training and testing data-sets for the satellite images are linked [here.](https://drive.google.com/drive/u/0/folders/1e5m7uNK1BXcI_C6u6h9o5WlL2Or4fo3K)

The following python modules were utilised:
```python
tensorflow
numpy
matplotlib
sys
h5py
IPython
```

There is also code that is used to build Recurrent Neural Network (RNN) models that **disaggregate** smart water meter readings into individual end uses for household services and appliances. The data-set ("household_water_consumption_identification.csv") is linked [here.](https://drive.google.com/file/d/1hDa4xMRLg5nuAXXG1EQM0X526-sz14to/view?usp=share_link) There is also a prediction of urban flooding. In this analysis I used FNNs, SimpleRNNs, as well as LSTMs to predict whether a certain storm event will result in flooding of an Urban area. The original input sequences are events of different length sampled at 5 minutes time resolution; the output is a binary variable which is equal to 1 in case flooding has occurred as a consequence of the storm.
