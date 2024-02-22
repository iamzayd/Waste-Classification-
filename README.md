# Waste Classification using Inception V3

## Overview
This repository contains the code and trained model for a waste classification system that categorizes waste into three main classes: Biodegradable, Non-Biodegradable, and Recyclable. The model is built upon the Inception V3 architecture, which is fine-tuned for our specific dataset.

![Training and Validation Loss and Accuracy](image.png)

## Model Details
The Inception V3 model has been trained using a custom dataset to classify waste into the following classes:
- Biodegradable (biodeg)
- Non-Biodegradable (non-biodeg)
- Recyclable (recyclable)

The training process and results are documented in the Jupyter Notebook `waste-clasification.ipynb`.

## Results
The Inception V3 model achieved the following performance:

Training Loss: Decreased significantly over epochs, indicating good model learning.
Validation Loss: Decreased and stabilized, showing good generalization.
Training Accuracy: Increased over epochs, showing consistent learning.
Validation Accuracy: Increased, indicating the model's ability to generalize from the training data.
The graph above shows the Training and Validation Loss and Accuracy over 4 epochs.
