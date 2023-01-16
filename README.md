# Fake-News-Classifier-Project

This project focuses on training a classification model to be able to accurately detect whether or not a news article is real or fake. The dataset used is from kaggle. After the dataset is preprocessed and cleaned, it is split into a training and testing dataset. The datasets were used to train and compare 3 different classification models: multinomial naive bayes, k nearest neighbors, and random forest. The results of the models are displayed in a table.

Created with:
- Python
- Juypiter Notebook

Main Python Libraries used:
- pandas
- sklearn

## News Classification Distribution
![News Classification](https://github.com/garlandzhao/Fake-News-Classifier-Project/blob/5fda9c07225d2bd8fd8488f76038baf5c91ce5fe/Fake%20News%20Classifier%20Project/Images/Pie%20chart.png)

The pie chart reveals that most of the news articles within the dataset are classified as fake. 50.34% of the news articles are fake while 49.66% of the news articles are real.

## Results

![Classification Model Results](https://github.com/garlandzhao/Fake-News-Classifier-Project/blob/5fda9c07225d2bd8fd8488f76038baf5c91ce5fe/Fake%20News%20Classifier%20Project/Images/Results.PNG)

The results of the 3 different models are displayed above. The most accurate model is the random forest model followed by the multinomial naive bayes model. The worse performing model is the k nearest neighbors model.

## Confusion Matrix

![Random Tree Confusion Matrix](https://github.com/garlandzhao/Fake-News-Classifier-Project/blob/5fda9c07225d2bd8fd8488f76038baf5c91ce5fe/Fake%20News%20Classifier%20Project/Images/Random%20Tree%20Confusion%20Matrix.png)

The image above displays the confusion matrix for the random forest model. A confusion matrix represents the accuracy of the model. The correct predictions of the model are located in the top left and bottom right quadrants of the matrix. The incorrect predictions are located in the other remaining quadrants.

## Note
- Dataset: https://www.kaggle.com/datasets/hassanamin/textdb3
- Due to the large file size of the dataset, it has been compressed and must be decompressed before usage
