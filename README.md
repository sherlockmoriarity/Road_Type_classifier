# ROAD CONDITION/TYPE CLASSIFIER

📁Training Data

The training data for this project consists of images sourced from Google Images, representing various road conditions: snowy, icy, pothole, and wet. Due to the large size of the dataset, it cannot be uploaded directly to the GitHub repository.

To obtain the dataset, please follow these steps:

1)Download Images: Search for the specific road conditions on Google Images.
2)Organize Images: Create separate folders for each road type (e.g., snowy, icy, pothole, wet).
TIP: Use 'Download All Images' Chrome Extension for easy download.
3)Prepare for Training: Place the organized images in a directory structure compatible with the training script.

💡Overview

The Road Type Classifier is a machine learning project aimed at classifying different types of road conditions using image data.

🔋This project uses convolutional neural networks (CNN) to identify and categorize roads into four types: snowy, icy, pothole, and wet.

🔍Features

👉Classifies road images into four categories: snowy, icy, pothole, and wet roads.

👉Utilizes TensorFlow with `tf.keras' for model training and evaluation.

👉Implements a CNN architecture for robust image classification of road conditions.

👉Accurately categorizes images into four types of road conditions: ❄️ snowy, 🧊 icy, 🕳️ pothole, and 🌧️ wet.

👉Includes image resizing and normalization techniques to prepare data for training.

👉Evaluates model performance using training and validation datasets.

👉Provides tools for visualizing accuracy and loss during training.

⚙️Tech Stack

👉Python

👉TensorFlow

👉Keras

👉NumPy

👉Matplotlib


🤸Quick Start

Make sure you have the following installed on your machine:
1.python
2.Git

🚨Cloning the Repository

git clone https://github.com/sherlockmoriarity/Road_Type_classifier.git

cd Road_Type_classifier

⚙️Training the Model 

🤖The model consists of:

👉Convolutional Layers to extract features from images.

👉Max Pooling Layers to reduce dimensionality and retain important features.

👉Dense Layers to make predictions based on the extracted features.

👉The final layer uses Softmax for multi-class classification, predicting one of four road conditions.

🤖The model is trained with road image data, using:

👉Categorical Cross-Entropy as the loss function.

👉Adam Optimizer for efficient training.


