# Cats vs Dogs Image Classification with SVM
#### This repository demonstrates how to build a machine learning model for classifying images of cats and dogs using Support Vector Machines (SVM). The model is trained on the Microsoft Cats vs. Dogs dataset, and the process includes preprocessing images, training the SVM classifier, and evaluating the model performance.

### Project Overview
#### This project uses a simple SVM classifier to distinguish between cat and dog images. The steps include:
#### 1. Data Preprocessing: Images are loaded, resized, converted to grayscale, and flattened to create feature vectors.
#### 2. Model Training: The data is split into training and testing sets, and an SVM classifier is trained on the data.
#### 3. Model Evaluation: The model's performance is evaluated using accuracy and a detailed classification report.
#### 4. Model Saving and Loading: The trained model is saved and loaded using joblib for future predictions.
#### 5. Image Prediction: A function is implemented to display an image along with its predicted label and the true label.

### Model Performance:
#### Accuracy: The model achieved an accuracy of 65.74% on the test set.
### Classification Report:
#### Precision, recall, and F1-score are provided for both Cat and Dog classes.
