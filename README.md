# Pyramid Vision Transformer: A Versatile Backbone for Dense Prediction without Convolutions

This repository contains PyTorch evaluation code, training code and pretrained models for PVT (Pyramid Vision Transformer).

Like ResNet, PVT is a pure transformer backbone that can be easily plugged in most downstream task models.


PyTorch 1.7.1 and CUDA101


## Data preparation

Download and extract CIFAR-100 train and val images.
/path/to/CIFAR-100: datasets01.

###Image Classification

## PVT-tiny
To train PVT-tiny on CIFAR-100 on a single node with a single gpu for 50 epochs run:
(uncomment the 44,45,246,382,383-line command in main.py)
python main.py
##ResNet18
To train PVT-tiny on CIFAR-100 on a single node with a single gpu for 50 epochs run:
(comment out the 44,45,246,382,383-line command in main.py)
python main.py