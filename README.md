# Soda-Bottle-Identification
This notebook is part of the soda bottle identification challenge hosted by Deep Cognition
[Soda Bottle Label Detection](http://deepcognition.ai/resources/competitions/soda-bottle-label-detection/)

Problem Description:
Human lambour is employed to ascertain if there is a need for restocking of soda bottles. This is intensive both in terms of time and effort. The aim of the challenge was to create a model to classify the soda bottle from its image. By doing so, one can find out the stock quantity present.

This notebook details the training and tuning of a ResNext-101 Deep CNN to achieve ~ 99% accuracy in classifying the soda bottles of 8 different varieties. 

The dataset contains in total ~ 6000 images with each class having ~ 800 images. 

The notebook details the following main points:

1. Finding the appropriate learning rate
2. Data Augmentation and employing Stochastic Gradient Descent with Restarts for optimizng the neural net.
3. Differential Learning Rate
4. Analysis of Results

A blog post detailing the approach is given in [link](https://medium.com/@santhoshetty/soda-bottle-identification-df001ce0614f)


