# No Brainer
No Brainer is a Flask-based web application designed for brain tumor detection using advanced image classification techniques. Powered by a ResNet50-based Convolutional Neural Network (CNN) model in PyTorch, this tool assists medical professionals in analyzing brain MRI images to detect tumors with high accuracy. By leveraging transfer learning, No Brainer achieves an impressive 97% accuracy, providing a reliable solution for medical image analysis.

## Features
1. Brain Tumor Detection: Classifies brain MRI images to identify the presence of tumors.
2. High Accuracy: Achieves 97% accuracy in tumor detection through a ResNet50 model with transfer learning.
3. User-Friendly Web Interface: Built with Flask, allowing users to upload MRI images and receive instant predictions.
4. OpenCV Integration: Uses OpenCV for image preprocessing to improve model accuracy and robustness.

## Technology Stack
- Deep Learning Framework: PyTorch with ResNet50 CNN model for image classification
- Web Framework: Flask for the application interface
- Computer Vision: OpenCV for image processing
- Deployment: Dockerized for easy setup and deployment

## Model Overview
The No Brainer model is based on a ResNet50 CNN architecture, fine-tuned through transfer learning to specialize in brain MRI analysis. This model was trained on a large dataset of brain MRI images to achieve high performance in identifying tumors.

## Installation
- Python
- Docker (for containerized setup)
- Tensorflow
- Flask
