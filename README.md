**American Sign Language (ASL) Detection**

This project demonstrates real-time detection and recognition of American Sign Language (ASL) static gestures (A-Z) using a Convolutional Neural Network (CNN). 
The goal is to enable communication for the Deaf and Hard-of-Hearing community by recognizing hand gestures and translating them into text.


**Dataset:**

The dataset was obtained from Kaggle ASL Alphabet Dataset: https://www.kaggle.com/datasets/grassknoted/asl-alphabet

The dataset contains images of static ASL gestures with the following details:
29 folders, each representing a class (A-Z, space, del, nothing).
Each folder contains 3000 images of 200x200 pixels.
A total of 87,000 images.

For this project, I used the gestures for:
Alphabets: A-Z



**Model Architecture**

**CNN Model:**

A custom Convolutional Neural Network (CNN) was designed to classify hand gestures.

Model includes:
Convolutional layers for feature extraction.
Pooling layers for dimensionality reduction.
Dense layers for classification.
Softmax activation for output probabilities.

Training:
The model was trained using the Kaggle dataset.
Optimized for high accuracy in recognizing static ASL gestures.


**Technologies Used**

Programming Language: Python

Libraries and Frameworks:

TensorFlow (for model building and training)

Mediapipe (for real-time hand landmark detection)

OpenCV (for video capture and frame processing)

Flask (for serving the model as a web app)

NumPy, Pillow (for preprocessing)

**Accuracy**

My model got an accuracy of **99.69% **

<img width="1542" alt="output" src="https://github.com/user-attachments/assets/0dffa761-de2b-486d-933a-2ae273e884e1">

