# Medical Image Classification using Pre-trained ResNet50 & VGG16

This project demonstrates how to classify **medical images** using two
powerful **pre-trained deep learning models**:

-   **ResNet50**
-   **VGG16**

Both models come pre-trained on **ImageNet**, and through **transfer
learning**, they are adapted to classify your custom medical image
dataset.

The project is built inside the notebook:

    Use_Pretrained_ResNet50_and_VGG16_Model_for_Medical_Image_Classifier.ipynb

## Features

-   Transfer Learning
-   Loads a custom image dataset
-   Applies preprocessing based on each model
-   Trains ResNet50 & VGG16 with custom classifier layers
-   Evaluates training and validation performance
-   Compares model accuracy

## Dataset Structure

    dataset/
       ├── class1/
       ├── class2/
       ├── class3/

## Workflow

1.  Import Libraries
2.  Load Image Paths
3.  Load Images & Labels
4.  Preprocess Images
5.  Build Models (ResNet50 & VGG16)
6.  Train Models
7.  Evaluate & Compare Performance

## Model Details

### ResNet50

-   ImageNet weights
-   Custom Dense layers added
-   Softmax output layer

### VGG16

-   ImageNet weights
-   Added fully connected classifier

## How to Run

``` bash
pip install tensorflow numpy matplotlib scikit-learn
```

Place dataset in `dataset/` then open:

    Use_Pretrained_ResNet50_and_VGG16_Model_for_Medical_Image_Classifier.ipynb

Run all cells.

## Project Structure

    project/
    │── dataset/
    │── models/
    │     ├── resnet50_model.h5
    │     ├── vgg16_model.h5
    │── Use_Pretrained_ResNet50_and_VGG16_Model_for_Medical_Image_Classifier.ipynb
    │── README.md
