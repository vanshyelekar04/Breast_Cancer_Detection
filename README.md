# Breast Cancer Detection using Neural Networks

This repository contains code for training and evaluating a neural network model to detect breast cancer using the Wisconsin Breast Cancer dataset.

## Dataset

The model is trained on the Wisconsin Breast Cancer dataset, which includes features computed from digitized images of fine needle aspirate (FNA) of breast mass. The task is to classify tumors into benign or malignant categories based on these features.

## Model Architecture

The neural network architecture used for this task consists of:
- Input layer with 128 neurons
- Hidden layers with 64 and 32, relu activation
- Output layer with 1 neuron and sigmoid activation for binary classification

## Files

- `breast_cancer_detection.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, evaluation, and visualization.
- `requirements.txt`: List of Python packages required to run the notebook.

## Usage

To run the notebook locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/vanshyelekar04/DeepLearn-Rx.git

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Open and execute breast_cancer_detection.ipynb in Jupyter Notebook or Google Colab.

## Results

**Accuracy achieved: 97%**
**Sensitivity (Recall) achieved: 97%**

**Feel free to customize this template according to your specific project details and preferences. Include any additional sections or information that would be useful for users and collaborators.**
