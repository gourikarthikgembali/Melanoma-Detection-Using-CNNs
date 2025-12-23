# Melanoma Skin Cancer Detection

This project uses a Convolutional Neural Network (CNN) to classify 9 types of skin lesions using the ISIC dataset.

## Features
- Loads and preprocesses dermoscopic images
- Trains a CNN model using TensorFlow
- Supports train/validation split
- Visualizes sample images and model performance

## Dataset
- Source: ISIC Skin Cancer Dataset
- Classes: 9 skin lesion categories
- Image size: 180×180
- Train/Test: 2249 / 118 images

## How It Works
1. Load dataset using `image_dataset_from_directory()`
2. Build a simple CNN model
3. Train the model in two phases (20 + 30 epochs)
4. Evaluate performance on unseen test images

## Requirements
- Python
- TensorFlow
- NumPy
- Matplotlib
- Google Colab (optional)

## Usage
- Place dataset in the expected folder structure
- Run the script or notebook
- View accuracy/loss plots and predictions

## Note
This model is for **educational purposes only** and not for clinical diagnosis.

Maintainer: Gouri Karthik Gembali
