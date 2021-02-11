# Fake-News-Classifier

## Dataset
 From Kaggle
 
 ## Description
- The dataset contains News, Title, Text, and Label as the attributes. 
- The pre-processing was done by removing stopwords, applying tokenization and lemmatization. 
- The output labels are classified as Fake and Real. For training the model, it was converted to the numerical form. 
- Then vectorization is applied to map words or phrases from vocabulary to a corresponding vector of real numbers which is used to find word predictions, word   similarities/semantics. The vectorizer objects provided by Scikit-Learn are used. 
- I fitted two Machine Learning models to the data namely, Naive-Bayes and Passive-Aggressive Classifier. And concluded that the passive-aggressive classifier performed the better here.
