# Brain tumor MRI classification
## Table of Contents
* [Introduction](#introduction)
* [Data Description](#data-description)
* [Methodology](#methodology)
* [Technology Stack](#technology-stack)

## Introduction
Project made in Jupyter Notebook with [Kaggle Brain tumors 256x256 dataset](https://www.kaggle.com/datasets/thomasdubail/brain-tumors-256x256), which aims at the classification of brain MRI images into four categories, using different CNN models.

## Data Description
Dataset contains 3096 images of human brain MRI scans divided into four categories: 
* Pituitary tumor
* Meningioma tumor
* Giloma tumor
* Normal - no tumor

## Methodology
1. **Data importing & augmentation** - Notebook starts with importing data and applying rescaling, rotation and horizontal flip to perform data augmentation.
2. **Data Visualization** - To get better understanding of data, sample from every category is being displayed along with it's label.
3. **Custom CNN model** - Custom Convultional Neural Network model is being build, trained and evaluated by accuracy score and Loss & Accuracy charts.
4. **Transfer Learning** - With help of VGG16 pretrained convultional base another model is developed, trained and evaluated as earlier.
5. **Fine tuning VGG16 model** - By allowing some of VGG16's convultional layers to be trainable model is being further trained to fit data better.

## Technology Stack
* Python 3.9.18
* Pandas 2.0.3
* Numpy 1.26.0
* Matplotlib 3.8.0
* Tensorflow 2.6.0
* Keras 2.6.0
