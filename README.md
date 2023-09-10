# MNIST
- Dataset - MNIST dataset; 60k train data, 10k test data

## Model 1 - KNN
Classification report:
              precision    recall  f1-score   support

           0       0.97      0.99      0.98       980
           1       0.96      1.00      0.98      1135
           2       0.98      0.97      0.97      1032
           3       0.96      0.97      0.96      1010
           4       0.98      0.97      0.97       982
           5       0.97      0.96      0.96       892
           6       0.98      0.99      0.98       958
           7       0.96      0.96      0.96      1028
           8       0.99      0.94      0.96       974
           9       0.96      0.96      0.96      1009

    accuracy                           0.97     10000
   macro avg       0.97      0.97      0.97     10000
weighted avg       0.97      0.97      0.97     10000

Confusion matrix:
array([[ 974,    1,    1,    0,    0,    1,    2,    1,    0,    0],
       [   0, 1133,    2,    0,    0,    0,    0,    0,    0,    0],
       [  10,    9,  996,    2,    0,    0,    0,   13,    2,    0],
       [   0,    2,    4,  976,    1,   13,    1,    7,    3,    3],
       [   1,    6,    0,    0,  950,    0,    4,    2,    0,   19],
       [   6,    1,    0,   11,    2,  859,    5,    1,    3,    4],
       [   5,    3,    0,    0,    3,    3,  944,    0,    0,    0],
       [   0,   21,    5,    0,    1,    0,    0,  991,    0,   10],
       [   8,    2,    4,   16,    8,   11,    3,    4,  914,    4],
       [   4,    5,    2,    8,    9,    2,    1,    8,    2,  968]],
      dtype=int64)

## Model 2 - SVM
Classification report:
              precision    recall  f1-score   support

           0       0.94      0.97      0.96       980
           1       0.96      0.99      0.97      1135
           2       0.90      0.93      0.91      1032
           3       0.89      0.93      0.91      1010
           4       0.92      0.94      0.93       982
           5       0.91      0.89      0.90       892
           6       0.96      0.93      0.95       958
           7       0.95      0.92      0.93      1028
           8       0.91      0.88      0.90       974
           9       0.93      0.89      0.91      1009

    accuracy                           0.93     10000
   macro avg       0.93      0.93      0.93     10000
weighted avg       0.93      0.93      0.93     10000

Confusion matrix:
array([[ 953,    0,    6,    2,    1,    8,    6,    2,    1,    1],
       [   0, 1118,    7,    2,    0,    1,    2,    1,    4,    0],
       [   9,   12,  956,   11,    9,    4,    5,    5,   18,    3],
       [   7,    1,   15,  940,    0,   17,    1,    6,   19,    4],
       [   3,    2,   18,    1,  927,    0,    3,    6,    3,   19],
       [   7,    6,    7,   40,    5,  791,   12,    1,   20,    3],
       [  14,    3,   17,    1,    9,   19,  892,    0,    3,    0],
       [   2,    8,   23,   14,   11,    2,    0,  945,    2,   21],
       [  11,    7,   10,   29,    8,   23,    8,    6,  860,   12],
       [   9,    7,    6,   11,   38,    5,    0,   23,   12,  898]],
      dtype=int64)

## Model 3 - CNN
Classification report:
              precision    recall  f1-score   support

           0       1.00      0.99      0.99       980
           1       0.99      0.99      0.99      1135
           2       0.99      0.99      0.99      1032
           3       0.99      1.00      0.99      1010
           4       1.00      0.99      1.00       982
           5       0.99      0.99      0.99       892
           6       1.00      0.99      0.99       958
           7       0.98      1.00      0.99      1028
           8       0.99      1.00      0.99       974
           9       0.99      0.99      0.99      1009

    accuracy                           0.99     10000
   macro avg       0.99      0.99      0.99     10000
weighted avg       0.99      0.99      0.99     10000

Confusion matrix:
array([[ 974,    0,    2,    0,    0,    0,    0,    1,    3,    0],
       [   0, 1129,    0,    2,    0,    0,    0,    3,    1,    0],
       [   0,    0, 1025,    0,    0,    0,    0,    7,    0,    0],
       [   0,    0,    1, 1005,    0,    3,    0,    0,    1,    0],
       [   0,    0,    0,    0,  977,    0,    0,    0,    0,    5],
       [   1,    1,    0,    7,    0,  880,    2,    1,    0,    0],
       [   3,    3,    2,    1,    2,    1,  944,    0,    2,    0],
       [   0,    1,    0,    0,    0,    0,    0, 1025,    1,    1],
       [   0,    0,    1,    0,    0,    0,    0,    2,  970,    1],
       [   0,    1,    0,    0,    2,    2,    0,    7,    1,  996]],
      dtype=int64)

## Model 4 - RF
Classification Report
               precision    recall  f1-score   support

           0       1.00      0.99      0.99       980
           1       0.99      0.99      0.99      1135
           2       0.99      0.99      0.99      1032
           3       0.99      1.00      0.99      1010
           4       1.00      0.99      1.00       982
           5       0.99      0.99      0.99       892
           6       1.00      0.99      0.99       958
           7       0.98      1.00      0.99      1028
           8       0.99      1.00      0.99       974
           9       0.99      0.99      0.99      1009

    accuracy                           0.99     10000
   macro avg       0.99      0.99      0.99     10000
weighted avg       0.99      0.99      0.99     10000

Confusion matrix: 
array([[ 968,    0,    1,    0,    0,    2,    4,    1,    4,    0],
       [   0, 1124,    2,    3,    0,    2,    2,    0,    1,    1],
       [   6,    0,  998,    8,    2,    0,    4,    8,    6,    0],
       [   0,    0,    9,  976,    0,    6,    0,    9,    8,    2],
       [   1,    0,    3,    0,  957,    0,    4,    0,    2,   15],
       [   3,    0,    0,    8,    3,  863,    6,    2,    4,    3],
       [   6,    3,    1,    0,    2,    4,  939,    0,    3,    0],
       [   1,    3,   17,    1,    1,    0,    0,  995,    1,    9],
       [   3,    0,    6,    8,    5,    5,    4,    5,  928,   10],
       [   5,    6,    2,   10,   11,    4,    1,    4,    3,  963]],
      dtype=int64)

## Model 5 - LR
Final Accuracy: tensor(92.4600)

I'm not sure how to show the classification report and confusion matrix from this, but I'll try to figure it out