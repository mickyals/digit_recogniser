# Digit Recognition Using SVM
> A classic problem in the field of pattern recognition is that of handwritten digit recognition. Suppose that you have images of handwritten digits ranging from 0-9 written by various people in boxes of a specific size - similar to the application forms in banks and universities.


## Objective
> Develop a model using Support Vector Machine which should correctly classify the handwritten digits from 0-9 based on the pixel values given as features.

## Data Description
For this problem, we use the MNIST data which is a large database of handwritten digits. The 'pixel values' of each digit (image) comprise the features, and the actual number between 0-9 is the label. Since each image is of 28 x 28 pixels, and each pixel forms a feature, there are 784 features.

## Contents
| File name | Description | Format |
|-----------|-------------|--------|
| test      | test dataset| csv    |
|train      | train dataset| csv    |
|final_predictions_test_data| final predictions| csv|
|cross_val_results| hyperparams | csv |
|Digit_Recognition_SVM| notebook | ipynb |


While a basic SVM worked well on the dataset, there were still over 780 attributes to consider so a dimensionality reduction was pursued using PCA. After identifying the PCs of the dataset, a new SVM model was made which slightly outperformed the original SVM model by 0.3% giving it an accuracy of 98%





## Credit

@misc{digit-recognizer,
    author = {AstroDave, Will Cukierski},
    title = {Digit Recognizer},
    publisher = {Kaggle},
    year = {2012},
    url = {https://kaggle.com/competitions/digit-recognizer}
}