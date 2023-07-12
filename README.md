# ResNet-50

This repository contains code and resources for training and using a ResNet-50 model to classify vehicles. The ResNet-50 architecture is a deep convolutional neural network that has shown excellent performance in image classification tasks.

## Dataset

The dataset used for training and evaluation is a collection of images of traffic in urban areas, including cars, trucks, motorcycles, and bicycles. The dataset is divided into training, validation, and test sets to ensure proper model evaluation. The images in the dataset are labeled with their corresponding vehicle types.

## Model Architecture

The model architecture used for vehicle classification is ResNet-50. ResNet-50 is a deep neural network architecture that has 50 layers and employs skip connections to address the vanishing gradient problem. It has been pretrained on a large dataset (such as ImageNet) and can be fine-tuned for specific tasks like vehicle classification.

## Setup
To use the code in this repository, follow these steps:

1. Clone the repository
   ```
   git clone https://github.com/your-username/vehicle-classification-resnet50.git
   cd vehicle-classification-resnet50


2. Install the required dependencies
3. Train the Model

note: You can take any dataset as per your needs , the model needs to be trained on the dataset of your choice

## Results

After training the model on the provided dataset, we achieved an accuracy of 93.75% on the test set. The performance of the model can be further improved by fine-tuning hyperparameters, increasing the dataset size, or employing additional techniques such as data augmentation.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

Feel free to contribute to this project by creating pull requests or opening issues. If you have any questions or suggestions, please contact the project maintainer.
