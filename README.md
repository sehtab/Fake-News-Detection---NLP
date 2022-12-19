# Fake-News-Detection-NLP


https://colab.research.google.com/drive/1W1GJ708d-RkB1z4ZiNvjiBm-RZ-PgkJw?usp=sharing



# Objective:

The objective of this ICP is to detect the fake news and for that the related dataset is uploaded and analyzed.

# Approaches

At first, necessary libraries are imported. The dataset is uploaded then tokenized and splitted. After split, trainset data is synthethized with word vector,
and PCA analysis is done. Then word level tf-idf, count word tf-idf is done over train dataset. 
Then train datset is analyzed with different classifier: Passive-Aggressive Classifier, MultinomialNaive Bayes Theorem and  SVC. 
All classifiers accuracy, precision, recall and F1 score is evaluated.

# Datasets

For this ICP from news.csv is used as dataset.

# Results:

Results are generated from sklearn library and they are working good. I am getting maximum accuracy from Passive-Aggressive classifier which is of 94% for word level tf-idf

# Challenges

For the case of Hashing vectorizer MNNB classification is not working, saying "ValueError: Negative values in data passed to MultinomialNB (input X)" 

# Planned Work

news.csv attached with the colab file.Then several tf-idf for classification and featureset is being created. After splitting the dataset in train and test 
with 20% in test set classifiers are implemented and classifiers are performance are evaluated through Accuracy, Recall, Precision and F1 -score.

![image](https://user-images.githubusercontent.com/70243598/192074624-971b76af-dbb2-47c6-9f35-68542a2068eb.png)

![image](https://user-images.githubusercontent.com/70243598/192074645-e03186ba-4047-4479-8356-aefc6efc25a8.png)
