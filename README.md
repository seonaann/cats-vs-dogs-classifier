 Cats vs Dogs Classifier using CNN (TensorFlow/Keras)
This project is a binary image classification model that distinguishes between images of cats and dogs using a Convolutional Neural Network (CNN). The model is built and trained using TensorFlow Datasets (TFDS) and Keras, and evaluated on a validation set.

Dataset
Dataset: Cats vs Dogs

Source: Microsoft Research

Images: 25,000 JPEG images of cats and dogs

Used: 80% for training, 20% for validation

Model Architecture
Input: 150x150 color images

3 Convolutional layers (32, 64, 128 filters)

3 MaxPooling layers

1 Flatten layer

1 Dense hidden layer (512 units)

1 Output layer (sigmoid activation)

 Tools & Libraries
Python

TensorFlow & Keras

TensorFlow Datasets (TFDS)

Google Colab

Matplotlib

 Results
Training Accuracy: ~87%

Validation Accuracy: ~81%

Loss function: Binary Crossentropy

Optimizer: Adam

 Sample Predictions
The model's predictions were visualized on a batch of validation images. Correct predictions are shown in green, incorrect ones in red.

 Model Saving
python
Copy
Edit
model.save("cats_vs_dogs_model.h5")





