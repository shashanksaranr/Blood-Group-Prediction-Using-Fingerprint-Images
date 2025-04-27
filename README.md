# Blood-Group-Prediction-Using-Fingerprint-Images

This project uses Convolutional Neural Networks (CNNs) implemented in PyTorch to predict blood groups based on fingerprint images. By analyzing unique fingerprint patterns, the model aims to classify a person’s blood group into categories such as A, B, AB, or O, offering a novel approach to biometric-based healthcare solutions.

# Key Features:

Dataset: Fingerprint images with associated blood group labels.

Preprocessing: The images are preprocessed for consistency and suitability in deep learning models.

Model Architecture: A CNN model extracts key features from the fingerprint images, followed by a fully connected layer to predict the blood group.

Framework: Built using PyTorch for flexibility and efficient model training.

# Technologies Used:

Python

PyTorch

OpenCV (image preprocessing)

Matplotlib/Seaborn (data visualization)

# How It Works:

Input: The model accepts a fingerprint image as input.

Feature Extraction: The CNN analyzes the image to detect distinguishing features.

Prediction: The model predicts the blood group based on the extracted features.

Output: The predicted blood group (A, B, AB, or O) is returned.

# Installation:

Clone the repository and install dependencies:

git clone https://github.com/your-username/blood-group-prediction.git

cd blood-group-prediction

pip install -r requirements.txt

# Usage:

1. Prepare a dataset of fingerprint images and their corresponding blood group labels.

2. Train the model with:

  python train.py

3. Make predictions with:

  python predict.py --image path_to_fingerprint_image
