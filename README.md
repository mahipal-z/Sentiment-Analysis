# Sentiment-Analysis
The goal of the project is to develop a machine learning model that can accurately classify the sentiment of product reviews as either positive or negative.

# Project Conclusion

* Our model accurately predicts 2/3rd of the product sentiment polarities (accuracy = 67%). This gives us a good confidence in labeling satifaction rate of product reviewers.
* Model can confidently identify a negetive sentiment (recall for '0' class labels = 90%), which is great as by identifying unhappy reviewers and compensating them can avoid opportunity loss in future and help maintain the popularity of brand.
* Out of all reviews that were predicted positive, 84% of them were labeled correctly (precision for '1' class = 84%).

## Next steps:

* Other promising classification models such as SVM, RandomForestClassifier of Neural Network model should be tried to see which gives the best accuracy.
* If more information is provided about prediction of which specific label (ie, positive or negetive sentiment) is more important for our business case, model can be further tuned to achieve either higher precision or recall value for that particular class.
