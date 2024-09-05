# Real/Artificial Image Discriminator

This project aims to develop a Convolutional Neural Network (CNN) model capable of distinguishing between real and AI-generated synthetic images. The dataset used for this task is sourced from the [CIFake dataset on Kaggle](https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images).

## Key Features
- **Model Architecture:** The model is a custom CNN built using PyTorch.
- **Cross-Validation:** Implemented a 5-fold cross-validation to ensure robustness and prevent overfitting.
- **Data Augmentation:** Applied random horizontal flipping and normalization to enhance model generalization.
- **Training:** Trained over multiple epochs with adaptive learning rate scheduling.
- **Evaluation:** Achieved an accuracy of 92.99% on test images.

## Getting Started

### Prerequisites
- Python 3.x
- PyTorch
- torchvision
- numpy
- scikit-learn

### Installation
Install the required Python packages using pip:

## Dataset
Download the CIFake dataset from Kaggle and extract it. The dataset should be structured as follows:

## Usage
1. **Prepare Data:** Update the `train_dir` and `test_dir` in the code to point to your dataset location.
2. **Train the Model:** Run the training script to start the training process with cross-validation.
3. **Evaluate the Model:** After training, the model will automatically evaluate and report accuracy on the test set.

## Results
- **Test Accuracy:** 92.99%

## License
This project is licensed under the MIT License.

## Acknowledgments
- Thanks to [Kaggle](https://www.kaggle.com/) for providing the dataset.
- Inspired by various implementations of CNNs for image classification tasks.

