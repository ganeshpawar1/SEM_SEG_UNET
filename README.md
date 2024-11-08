
#Semantic Segmentation of Satellite Images Using UNet

This project implements semantic segmentation on satellite images of Dubai using a basic UNet architecture. Semantic segmentation is a deep learning technique that involves classifying each pixel in an image to identify objects or regions of interest, such as buildings, roads, vegetation, and water bodies in satellite imagery. The UNet model is particularly well-suited for this task due to its encoder-decoder structure, which enables precise localization and boundary detection.

#Project Overview

The goal of this project is to accurately segment satellite images of Dubai into meaningful classes. The UNet model, a popular choice for biomedical and satellite image segmentation, is employed here due to its ability to learn spatial hierarchies effectively while retaining high-resolution output.

#Key Components

Dataset and Preprocessing:

    Satellite Imagery of Dubai: 
    Complex urban landscape ideal for  testing semantic segmentation models.

Image Patching:

    Large images are divided into smaller patches to facilitate training and improve model performance on high-resolution data.
        
Model Architecture: 

    A basic UNet structure, which includes:
    Encoder Path: Captures contextual features through a series of convolutional layers and pooling.
    Decoder Path: Reconstructs spatial details using upsampling layers and skip connections from the encoder, which assists in precise segmentation.


Training: 

    The model learns to classify each patch’s pixels into various classes, enabling detailed analysis on a smaller scale.