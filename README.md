# Heart Disease Detection with Deep Learning

This repository contains a Jupyter Notebook that demonstrates the implementation of a deep learning model for heart disease detection. The dataset used in this project is the Cleveland Clinic Heart Disease dataset, which contains information on 303 patients with heart disease.

The notebook is divided into the following steps:

1. **Data preprocessing:** The features and labels are extracted from the dataset, the train and test sets are split, and the dataset is normalized.
2. **Model architecture:** A deep neural network is created using the TensorFlow and Keras libraries. The network consists of a dense layer with 128 neurons, followed by a dropout layer with a rate of 0.2.
3. **Model training:** The network is trained using the train dataset.
4. **Model evaluation:** The network is evaluated using the test dataset.

The results show that the model achieves an accuracy of 95% on the train dataset and 85% on the test dataset. This suggests that the model is overfitting the train dataset. To address this, the learning rate could be reduced or the dropout rate could be increased.

**Setup**

To run the notebook, you will need the following Python libraries:

- TensorFlow
- Keras
- NumPy
- Pandas
You can install these libraries using the following command:

```
pip install tensorflow keras numpy pandas 
```

