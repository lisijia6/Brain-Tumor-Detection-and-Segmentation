# Brain-Tumor-Detection-and-Segmentation

This is the code base for a data science project: Brain Tumor Detection and Segmentation.

## Introduction 
Since certain image features may not be easily captured by human eyes and manual tumor classifications can be time-consuming, the main goal of this project is to explore various neural network models to automatically classify between 3 types of brain tumors from MRI scans. This can help provide diagnosis suggestions which can release healthcare workers from spending time reading MRI scans so that they can spend more time on patients. The secondary project goal is to detect and segment the tumor from the MRI scans. This can be useful for pinpointing the exact location of the tumor for supporting physicians’ decisions in making treatment plans for the patients. The data contains 3,064 images of 3 brain tumor types from 233 patients. Data cleaning and preprocessing are performed to convert the data into a consistent format, including resizing images, converting data to NumPy array types, applying one-hot-encoding on response variable, performing data normalization, splitting data into train and test sets, oversampling to rebalance data, and augmenting data. For brain tumor classification, baseline feed-forward neural network (FFNN) and advanced convolutional neural network (CNN) are implemented. The CNN model is visualized using activation maps and saliency maps. For tumor detection and segmentation, we implemented UNet as a baseline model, and LinkNet and DeeplabV3+ as advanced models. Experiments show that advanced models outperform the baseline models in terms of accuracy and segmentation quality. Overall, deep learning models are powerful tools for detecting and segmenting brain tumors, and the results obtained show promising potential for clinical use.

## Usage
Code is contained in ./notebook directory. Run the ipynb notebook to reproduce the results.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code according to the terms specified in the license.