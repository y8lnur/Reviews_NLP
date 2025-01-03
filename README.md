# Reviews_NLP
 
This project parses Reviews from the web page of one of the restaurants in Almaty.
It has over than 5000 reviews.
In the code you can see different data wrangling, analysis and visualizations and some insights from them.
The important part of it, that I implemented the NLP, Naive Bayes algorithm to train a model on the parsed data.
This model shows great results in the confusion matrix and in the classification report:
High Accuracy: The overall accuracy is 93%, which is a good indicator of the model's ability to correctly classify instances.
Balanced Precision and Recall: Both precision and recall are high for both classes (0 and 1), suggesting a good balance between correctly identifying positive instances and avoiding false positives.
F1-Score: The F1-score, which is the harmonic mean of precision and recall, is also high for both classes, further indicating good performance.
Confusion Matrix: The confusion matrix visually confirms the model's performance. The diagonal elements (True Positives and True Negatives) have high values, indicating accurate predictions. The off-diagonal elements (False Positives and False Negatives) are relatively low, suggesting that the model is making few errors.
![image](https://github.com/user-attachments/assets/03335a1c-c459-4558-a2b7-c86ced1efbe8)
Of course there might be room for improvement, but the whole code was written in couple days in total of 5-6 hours.
I think results are pretty good.
Also there is a funciton in the end of the code, where you can write your own review and It will check if its positive or negative!
