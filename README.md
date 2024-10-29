# Fish-Images-Classification-with-ANN

still under development!!!

### Project Purpose 
The aim of this project is to develop a deep learning model that can accurately classify fish images species. The model takes fish images data as input and determines which species these images belong to.

### Dataset
In the project, the "A Large Scale Fish Dataset" dataset on the Kaggle platform was used. This dataset contains images of 9 different fish species.

### Operational Flow of the Code
- Importing Libraries 
- Upload the dataset: Uploading the data set consisting of pictures of fish species.
- Convert Image Data to Numeric Data: We need to convert image data to numeric data because we 
 need input as numeric.
- Test and Train dataset Spliting
- Label Encoding and One-Hot Encoding for class labels
- Data Normalization
- Creating Model
##### Model Summary

| Layer (type)    | Output Shape   | Param #    |
| --------------- | -------------- | ---------- |
| dense_8 (Dense) | (None, 512)    | 6,291,968  |
| dropout_7 (Dropout) | (None, 512) | 0          |
| dense_9 (Dense) | (None, 256)    | 131,328    |
| dropout_8 (Dropout) | (None, 256) | 0          |
| dense_10 (Dense) | (None, 128)   | 32,896     |
| dropout_9 (Dropout) | (None, 128) | 0          |
| dense_11 (Dense) | (None, 64)    | 8,256      |
| dropout_10 (Dropout) | (None, 64) | 0          |
| dense_12 (Dense) | (None, 9)     | 585        |

 Total params: 6,465,033 (24.66 MB)
 Trainable params: 6,465,033 (24.66 MB)
 Non-trainable params: 0 (0.00 B)

 ### Model Performance
Model Performance Test Loss:  2.1978471279144287 Test Accuracy:  0.0994444414973259 These results show that the model performs poorly on the training data and is inconsistent on the validation set.

### Kaggle Source 
https://www.kaggle.com/code/ayenurtak/fish-images-classification-with-ann
