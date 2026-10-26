# EuroSAT — CNN vs MobileNetV3 Transfer Learning

## Overview

Satellite image classification using the EuroSAT dataset, comparing a Convolutional Neural Network (CNN) trained from scratch with a pre-trained MobileNetV3 model using Transfer Learning.

## Dataset

EuroSAT contains 27,000 Sentinel-2 satellite images distributed across 10 land-use and land-cover classes.

## Models

- **Custom CNN:** A simple convolutional neural network trained from scratch.
- **MobileNetV3-Small:** A pre-trained ImageNet model adapted to classify the 10 EuroSAT classes, with frozen feature extraction layers.

## Evaluation

Model performance is evaluated using training and validation accuracy, test accuracy, and confusion matrices.

## Technologies

Python, PyTorch, TorchVision, NumPy, Matplotlib, Scikit-learn.

## Objective

Explore Transfer Learning and compare its performance with a CNN trained from scratch on satellite imagery.
