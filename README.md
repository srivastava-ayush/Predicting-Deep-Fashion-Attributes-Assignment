# Predicting-Deep-Fashion-Attributes-Assignment

## Data Preprocessing
* Filename: Data_Preprocessing_Final.ipynb
* Input: Folder Containing Images and Attributes csv (both should be in same folder as jupyter notebook)
* Output: Images and attributes split into train, test validatin data and saved in different folders and csv files after removing NaN values, removing duplicates etc. Data after sliptting is stored in folder named "split_data".
* In Data Preprocessing, MLSMOTE( Multi Label Synthetic Minority OverSampling Technique) could have been explored to reduce bias but it could not be possible in the given timeframe.

## Model Training
* Filename: Inception_Final.ipynb
* Input: Train and validation images and respective CSVs.
* Output: Model Weights in .h5 format. Two different models are returned, one corresponds to best validation accuracy achieved while training, second is the model after last epoch.

## Inference
* Filename: Inference_Final.ipynb
* Input: Model in .h5 format and test images and attributes CSV.
* Output: test_predictions.csv, presdictions of the test data in csv format similar to initial attributes.csv.
