# Machine Learning: Classifiers

This was a homework assignment from my "Programming Machine Learning Applications" class.
The focus of this assignment was on classifying functions using 3 different data sets.
## Part 1
The first data set was a collection of text, which was a set of 1000 documents that were either related to where each observation was one of two classes: Hockey (class label 1) and Microsoft Windows (class label 0).
For this data set I created KNN classifier function. My training data is in the Row-Column format of term/Document
That means that the ijth entry is the frequency of the ith term in the jth document

I used two type of similarity functions: Euclidean distance and Cosine Similarity. For text data, cosine similarity is supposed to work better since degree difference between observations is not effected by spatial difference (as in Euclidean distance)
c. Your classifier should work with Euclidean distance as well as Cosine Similarity.
I created a function to compute the classification accuracy over the test data set, and then used the function on the test data.

I then repeated the entire above classification process using the dataset converted to TFxIDF weights instead of raw frequencies of terms.

## Part 2 
In part two I used a dataset from a bank (data located here: http://facweb.cs.depaul.edu/mobasher/classes/csc478/Data/bank_data.csv ) Then, using sckit learn, I created a KNN, decision tree, and Naive Bayes Classifier.

## Part 3
I used a socioeconomic dataset here. Additional classifiers were creatd with scikit-learn (KNN, LDA, and Decision Tree). I used 10-fold cross-validation to train the models here
