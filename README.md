# fetal-biometry-landmark-detection

# Fetal Biometry Landmark Detection

This repository contains code for the fetal biometry landmark detection challenge. The goal of this project is to develop algorithms capable of accurately identifying biparietal diameter (BPD) and occipitofrontal diameter (OFD) landmark points in fetal axial images. 

## Dataset

The dataset consists of fetal axial images annotated with BPD and OFD landmark points. The images are stored in the `images` directory, and corresponding annotations are stored in the `masks` directory.

## Code Structure

- `Part_A_Landmark.ipynb`: Jupyter Notebook containing code for the landmark detection-based approach.
- `Part_B_segmentation.ipynb`: Jupyter Notebook containing code for the segmentation-based approach.
- 


Open and run the Jupyter Notebooks (`Part_A_Landmark.ipynb` and `Part_B_segmentation.ipynb`) to train and evaluate the models.

## Results

The results of the experiments conducted on the dataset are summarized in the Jupyter Notebooks. Evaluation metrics such as accuracy, mean absolute error, and intersection over union are reported.

## Model Weights

The trained model weights are saved in the `model_weight` directory.
