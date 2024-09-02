# ReefVision-AI
An advanced deep learning model using VGG19 and other DL models to accurately classify coral reef images, enhancing conservation efforts through AI.
# Coral Reef Classification with ReefVision-AI
![OIP (1)](https://github.com/user-attachments/assets/0392181b-5768-483d-9fa6-85a28389da63)


![densenet](https://github.com/user-attachments/assets/901da235-ffb4-4b9d-8dd1-76b8c87362ad)


## Overview

**ReefVision-AI** is a deep learning project aimed at classifying coral reef images into two categories: `healthy_corals` and `bleached_corals`. The project leverages convolutional neural networks (CNNs) and the VGG19 architecture to analyze and classify images with a high degree of accuracy.

## Key Features


- **In-Depth Data Exploration and Visualization**: 
  - Comprehensive exploratory data analysis (EDA)
  - Insightful visualizations to understand coral reef images
  - Identification of patterns and potential issues affecting model performance

- **Robust Data Preprocessing Techniques**:
  - High-quality data preprocessing pipeline
  - Image augmentation to expand the training dataset
  - Techniques include random rotations, flips, and color adjustments

- **Utilization of Pre-Trained VGG19 Model**:
  - Base architecture: VGG19, known for superior image classification
  - Extracts complex features, enhancing model performance

- **Incorporation of Advanced Callbacks**:
  - **Early Stopping**: Halts training to prevent overfitting
  - **Learning Rate Reduction**: Adjusts learning rate for smoother convergence
  - **Model Checkpointing**: Saves model regularly to keep the best-performing version

- **Thorough Evaluation of Model Performance**:
  - Accurate assessment using a separate test dataset
  - Provides insights into model generalization and areas for improvement

- **Intuitive Visualization of Predictions**:
  - Visual comparison of model predictions with ground truth
  - Assesses performance qualitatively and identifies patterns or errors

![dsds](https://github.com/user-attachments/assets/9cdca884-da7a-43b5-9049-aebe479b5840)


## Project Structure

The project is organized into the following components:

1. **Data Exploration and Visualization**: Script for exploring the dataset, including data distribution and random sample visualization, as well as techniques to check for corrupted images.

2. **Data Preprocessing**: Image augmentation to enhance model robustness, and data splitting into training, validation, and testing sets.

3. **Model Architecture**: Utilizes a pre-trained VGG19 model as the base with added custom layers for classification.

4. **Model Training and Evaluation**: Training of the model with various callbacks, and evaluation of model performance on test data, including visualization of training and validation metrics.

5. **Prediction and Analysis**: Generating predictions and comparing them with ground truth, as well as confusion matrix and classification report generation.



  ![res op 2](https://github.com/user-attachments/assets/aa11cc4e-6c96-4bac-9384-bc0ec22103de)


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- The VGG19 model weights are downloaded from TensorFlow's model repository.
- The dataset used is sourced from https://www.kaggle.com/datasets/vencerlanz09/healthy-and-bleached-corals-image-classification.

