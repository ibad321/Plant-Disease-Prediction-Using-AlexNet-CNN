# Plant Disease Prediction Using AlexNet CNN
This project focuses on predicting plant diseases using the AlexNet Convolutional Neural Network (CNN) architecture. The dataset used for this analysis consists of images of plants affected by various diseases. The goal is to classify these images into different disease categories using deep learning techniques.

## Dataset

The dataset used for this project is sourced from [https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset]. It contains images of plants affected by various diseases, along with corresponding labels indicating the type of disease present in each image.

## Project Workflow

1. **Data Preprocessing**
   - Loading and preprocessing the image data.
   - Augmenting the images to increase the diversity of the dataset.

2. **Model Architecture**
   - Building the AlexNet CNN model with the following layers:
     - Convolutional layers with ReLU activation.
     - Max pooling layers for downsampling.
     - Fully connected layers.
     - Softmax layer for classification.

3. **Model Training**
   - Compiling the model with appropriate loss function and optimizer.
   - Training the model on the training data.

4. **Model Evaluation**
   - Evaluating the model on the test data to determine its accuracy and performance.
   - Generating a confusion matrix to visualize the model's performance.

## Tools and Technologies

- **Python Libraries:** TensorFlow and Keras for building and training the model.
- **Image Processing Libraries:** OpenCV for image loading and preprocessing.
- **Model Visualization:** Matplotlib for visualizing model performance.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/plant-disease-prediction.git
