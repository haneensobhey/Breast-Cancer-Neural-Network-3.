# Breast Cancer Classification using Neural Networks

## Project Overview
This project uses an Artificial Neural Network (ANN) built with TensorFlow/Keras to classify breast cancer cases into two categories: benign and malignant.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- TensorFlow / Keras

## Workflow
1. Load and inspect the dataset.
2. Separate features and target labels.
3. Encode the target labels.
4. Split the data into training and testing sets.
5. Standardize the input features.
6. Build and train a neural network.
7. Evaluate performance using a confusion matrix and classification report.
8. Visualize training and validation loss and accuracy.

## Model Architecture
- Input: 30 features
- Hidden layer 1: 32 neurons, ReLU
- Hidden layer 2: 16 neurons, ReLU
- Hidden layer 3: 16 neurons, ReLU
- Output: 1 neuron, Sigmoid

## Preliminary Results
- Test accuracy: approximately 96.5%
- Precision, recall, and F1-score are evaluated for both classes.

## Disclaimer
This is an educational machine learning project and is not intended for clinical diagnosis.
