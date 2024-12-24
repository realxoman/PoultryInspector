# Poultry Inspector: Classification of Chicken Images

This project aims to classify chicken images as either "fresh" or "defrosted" using a machine learning model built with PyTorch.

## Project Overview

This project leverages a Convolutional Neural Network (CNN) based architecture, EfficientNet-B0, to perform classification on images of poultry. The images are collected from two categories: **fresh** and **defrosted** chicken.

## Prerequisites

To run this project, you'll need the following dependencies:

- Python 3.x
- PyTorch
- torchvision
- matplotlib
- scikit-learn
- PIL (Python Imaging Library)

Install the required libraries using `pip`:
```bash
pip install torch torchvision matplotlib scikit-learn pillow
‍‍‍‍‍```


## Download Dataset
To download the dataset, please refer to the [Download Dataset Guide](dataset/Download.md).

```bash
PoultryInspector/
  ├── train/
  │    ├── defrost/
  │    └── fresh/
  └── test/
       ├── defrost/
       └── fresh/
```

