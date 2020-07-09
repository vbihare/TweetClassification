# TweetClassification
The aim of this work is to categorize incoming tweets automatically into several predefined classes. Hence, this project can be termed a multi-class categorization problem. 
Below are the 3 modeling steps we will be using here:

1. Vectorize: This step transforms text data into numerical data that can be used for classification. You can read more about it here https://en.wikipedia.org/wiki/Bag-of-words_model

2. TF-IDF: This is an additional transformation that is common when working with text data. It uses statistical properties of the dataset to assign weights to text terms. You can read more about it in the below mentioned link.
https://en.wikipedia.org/wiki/Tf%E2%80%93idf

3. Classifier: Finally, we classify data that was transformed by the previous two steps. In this case we are using a linear support vector classifier, which is commonly used in text classification tasks. You can read more about it in the below mentioned link.
https://en.wikipedia.org/wiki/Support_vector_machine#Linear_SVM
