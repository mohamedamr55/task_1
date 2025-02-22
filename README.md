📌 What this project does:
Data Preprocessing:

Loads the MNIST dataset (handwritten digits 0-9).
Converts grayscale images to RGB (3 channels) for compatibility with CNN models.
Resizes images to 224x224 to match ResNet18 input requirements.
Model Selection & Modification:

Uses a pre-trained ResNet18 model from PyTorch.
Replaces the final fully connected layer to classify 10 digits (0-9).
Training Process:

Uses CrossEntropyLoss as the loss function.
Optimizes the model using Adam optimizer.
Trains the model for 5 epochs with batch size = 32.
Model Evaluation:

Evaluates the model on the test dataset.
Calculates accuracy based on correct predictions.
Results & Performance:

Displays loss per epoch during training.
Computes final accuracy on test data.
