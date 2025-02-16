# Participation_Assignment ( Neural Network )

## Objective
Build, compile, and train a neural network using TensorFlow.

## Dataset
- **Dataset Used**: MNIST
- **Preprocessing**:
  - Features (X): Normalized to values between 0 and 1.
  - Labels (Y): One-hot encoded for multi-class classification.

## Model Architecture
- **Input Layer**: Accepts data in the appropriate shape for the dataset.
- **Hidden Layer**: Dense layer with 128 neurons, ReLU activation.
- **Output Layer**: Dense layer matching the number of classes in the dataset, Softmax activation.

## Compilation and Training
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy
- **Metrics**: Accuracy
- Trained for a specified number of epochs with validation data.

## Model Features
- The model was saved in HDF5 format for future use.
- Predictions were made on test data to demonstrate its functionality.

## Proof of Participation
- **GitHub Repository Link**: https://github.com/madol-abraham/Participation_Assignment.git
- **Colab version history screenshot**: ![Image](https://github.com/user-attachments/assets/7e2ef952-db5b-49d3-b3f3-86b1e82cbf01).

## Contributors
1. Madol Abraham Kuol Madol
2. Geu Aguto Garang Bior
