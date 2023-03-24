# credit-risk-classification

I use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Two Logistic Regression Models have been performed, one with the original data and the other with oversampled data. A balanced accuracy score, confusion matrix, and classification report have been calculated, with the results showing like the following: 


<img width="912" alt="Screenshot 2023-03-23 at 8 41 14 PM" src="https://user-images.githubusercontent.com/115575880/227395456-07547a8b-f5fa-4a4b-8e2e-a35efccd64ee.png">
<img width="916" alt="Screenshot 2023-03-23 at 8 41 24 PM" src="https://user-images.githubusercontent.com/115575880/227395450-9657f2d2-aa5f-4499-a180-e5a861f76087.png">


As shown above, the test with the oversampled data (2nd screenshot) is more accurate, with the recall and f1-score being .99 and .91 as opposed to the original data (.91 and .88, respectively). It shows that oversamplification of data is results increases prediction accuracy by a reasonably siginificant amount, thus encouraged to use especially money-lending companies.
