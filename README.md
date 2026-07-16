# intel-image-classification

This code trains two CNN architectures on the intel image classification dataset to classify images into 6 labels.

Required Libraries:

* os
* cv2
* numpy as np
* kagglehub
* tensorflow as tf
* from tensorflow import keras
* from sklearn.preprocessing import LabelBinarizer
* from tensorflow.keras.optimizers import SGD
* pandas as pd
* from sklearn.metrics import accuracy_score, precision_score
* matplotlib.pyplot as plt

Important note: Use a high resource TPU (I used L4) as there are 16 combinations of architectures, optimizers, batch sizes, and learning rates.
