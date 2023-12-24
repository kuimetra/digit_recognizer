## About the Project

The main goal of the project is to develop a model capable of classifying handwritten hexadecimal characters efficiently
and accurately. It utilizes an adapted version of the EMNIST (Extended MNIST) dataset, consisting of over 107,000
labeled, grayscale images of 20x20 pixels each. These images represent 17 distinct classes, which include the digits
0-9, the letters A-F, and an additional class for empty images. To ensure the model's effectiveness, various machine
learning techniques, including K-Nearest Neighbors, Decision Trees, Support Vector Machines, Random Forest, and
Convolutional Neural Networks, were employed and evaluated.

To prepare the dataset for model training, a comprehensive preprocessing approach was implemented. Class imbalance
issues in the dataset were addressed using the Synthetic Minority Over-sampling Technique (SMOTE) and class weights.
Data denoising and dimension reduction were achieved through the application of a denoising autoencoder and Principal
Component Analysis (PCA), respectively; enhancing the dataset’s suitability for training effective machine learning
models. The Convolutional Neural Network outperformed other models,
achieving a test accuracy of 97.72%.

## Required Libraries

Install the following Python libraries before running the notebook:

- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow
- keras
- imbalanced-learn
- visualkeras

Use the following command to install all required libraries at once:

```bash
pip install numpy matplotlib seaborn scikit-learn tensorflow keras imbalanced-learn visualkeras
```

## How to Run

To run the project, open and execute the 'main.ipynb' Jupyter notebook in sequence.

> It's important to note that the complete execution takes approximately 70 minutes; however, for the sake of
> convenience, the notebook has been pre-run. All results showcased are reproducible and can be validated for consistency
> and reliability by restarting the kernel and re-executing all cells in the prescribed order.

## Report File

The project includes a report file that provides detailed explanations of each step involved in the implementation,
evaluation, and comparison of the machine learning models used for handwritten character classification. Each section of
the report is meticulously prepared, offering insights into the data preprocessing, model training, hyperparameter
tuning, and evaluation processes. The report is enriched with visualizations to offer a clearer understanding of the
models and the underlying data.
