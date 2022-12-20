# ECG-Arrhythmia-Detection-using-Image-based-CNN

Image datasets are derived from the ptbdb dataset from Kaggle https://www.kaggle.com/datasets/shayanfazeli/heartbeat

data_visualization.ipynb is meant for simple data visualization of the entries in the dataset

data_to_image_converter.ipynb is used to generate the image dataset from the csv

ptbdb_csv_model.ipynb trains the RNN based on the numerical values of the csv

ptbdb_image_model.ipynb trains the CNN model based on the image dataset generated from the csv dataset

ptbdb_image_model2.ipynb trains the CNN model based on a downsampled image dataset generated from the csv dataset





image_rescaler.ipynb rescales new test data into the right dimensions for use in the model

