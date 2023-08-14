# Chest X-ray Classification with CNN and Feature Drooping

This project uses a Convolutional Neural Network (CNN) to classify chest X-ray images into three categories: normal, bacterial pneumonia, and viral pneumonia. By employing a feature drooping technique, we've improved our model accuracy from 90% to 92%. 

## Dataset

The dataset utilized in this project is sourced from Kaggle. It consists of chest X-ray images labeled into the three aforementioned categories. 
(https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)


## Feature Drooping

To achieve improved performance, we experimented with feature drooping. This technique involves omitting certain features or channels from the input data to see if performance improves. The rationale behind this is that not all features contribute equally to the prediction, and some might even introduce noise.


## Getting Started

### Training

1. Clone this repository.
2. Download the dataset from Kaggle.
3. Run the jupyter notebook.

### Evaluation

In some case, the feature dropping improve the perfromace with 2%.
