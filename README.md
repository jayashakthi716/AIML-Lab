Exercise1 Output
DFS in Binary Search Tree:
Enter the element to search using DFS: 20
Element found in BST using DFS.

BFS in Binary Search Tree:
Enter the element to search using BFS: 7
Element found in BST using BFS

Exercise2 Output:
Start:  1 2 3 4 5 6 0 7 8
Goal:   1 2 3 4 5 6 7 8 0
--- A* Search ---
Steps to reach goal:
[1, 2, 3]
[4, 0, 5]
[6, 7, 8]

[1, 2, 3]
[4, 5, 0]
[6, 7, 8]

Total steps: 1
--- Memory-Bounded A* (IDA*) ---
Steps to reach goal:
[1, 2, 3]
[4, 0, 5]
[6, 7, 8]

[1, 2, 3]
[4, 5, 0]
[6, 7, 8]

Total steps: 1



Exercise3 Output:
Linear Regression:
MSE: 442.24
R² : 0.9278
Polynomial Regression (degree = 2):
MSE: 49.74
R² : 0.9919
<img width="681" height="423" alt="image" src="https://github.com/user-attachments/assets/863572bb-f2f9-4e96-a648-bbfacc65743f" />


exercise4 output:
First 5 rows of dataset:
       sepal length (cm)  sepal width (cm)  petal length (cm)  petal width (cm) species
0                  5.1               3.5                1.4              0.2    setosa
1                  4.9               3.0                1.4              0.2    setosa
2                  4.7               3.2                1.3              0.2    setosa
3                  4.6               3.1                1.5              0.2    setosa
4                  5.0               3.6                1.4              0.2    setosa

Model Accuracy: 1.0

Classification Report:
	               Precision	recall	 f1-score	   support

  setosa       	 1.00      	1.00     1.00        	19
  versicolor     1.00      	1.00     1.00        	13
  virginica      1.00      	1.00     1.00        	13

  accuracy        			             1.00		      45
  macro avg	     1.00		    1.00     1.00        	45
  weighted avg   1.00		    1.00     1.00		      45
<img width="975" height="517" alt="image" src="https://github.com/user-attachments/assets/bd61e04b-b65a-459d-9ac6-4d73cf63642c" />

Exercise5 output:
Sample Data:
label                            text
0   ham  Subject: enron methanol ; meter # : 988291\r\n...
1   ham  Subject: hpl nom for january 9 , 2001\r\n( see...
2   ham  Subject: neon retreat\r\nho ho ho , we ' re ar...
3  spam  Subject: photoshop , windows , office . cheap ...
4   ham  Subject: re : indian springs\r\nthis deal is t...

Model Accuracy: 0.9916237113402062

Classification Report:
               precision    recall  f1-score   support

         Ham       1.00      0.99      0.99      1121
        Spam       0.98      0.99      0.99       431

    accuracy                           0.99      1552
   macro avg       0.99      0.99      0.99      1552
weighted avg       0.99      0.99      0.99      1552

New Email Predictions:
'Congratulations! You've won a $1000 Walmart gift card. Click here to claim now.' → Spam
'Hi John, just wanted to confirm our meeting tomorrow at 10 AM.' → Ham

exercise 6 output:
Classification Report:
              precision    recall  f1-score   support
           0       1.00      1.00      1.00         8
           1       1.00      0.93      0.97        15
           2       0.88      1.00      0.93         7
    accuracy                           0.97        30
   macro avg       0.96      0.98      0.97        30
weighted avg       0.97      0.97      0.97        30

<img width="455" height="413" alt="image" src="https://github.com/user-attachments/assets/0c6dcb17-02cc-4f03-ac27-2a25d5e010e8" />

exercise 7 output:
<img width="545" height="428" alt="image" src="https://github.com/user-attachments/assets/6ef4fd1c-b1f1-40bc-a512-f60b19e7912a" />

exercise 8 output:
Model Accuracy: 0.8472
Classification Report:
              	 precision    recall  f1-score   support

    Negative       0.84      0.86      0.85     12500
    Positive       0.86      0.83      0.84     12500

    accuracy                           0.85     25000
   macro avg       0.85      0.85      0.85     25000
weighted avg       0.85      0.85      0.85     25000

New Review Predictions:
'This movie was absolutely fantastic! The story, the acting, everything was great.' → Positive
'I hated this movie. It was boring and a complete waste of time.' → Negative

exercise 9 output:
+---------+------------+
| age(29) | 0.00330033 |
+---------+------------+
| age(34) | 0.00660066 |
+---------+------------+
| age(35) | 0.0132013  |
+---------+------------+
| age(37) | 0.00660066 |
+---------+------------+
| age(38) | 0.00990099 |
+---------+------------+
| age(39) | 0.0132013  |
+---------+------------+
print(model.get_cpds('sex'))
OUTPUT 
| sex(0) | 0.316832 |
+--------+----------+
| sex(1) | 0.683168 |

print(model.get_cpds('exang'))
OUTPUT 
| exang(0) | 0.673267 |
+----------+----------+
| exang(1) | 0.326733 |
+----------+----------+

print(model.get_cpds('chol'))
OUTPUT 
| target    | target(0)            | target(1)            			                    |
+-----------+----------------------+--------------------------------------------------- +
| chol(126) | 0.0                  | 0.006060606060606061 		                        |
+-----------+----------------------+----------------------------------------------------+
| chol(131) | 0.007246376811594203 | 0.0                 	 	                        |
+-----------+----------------------+----------------------------------------------------+
| chol(141) | 0.0                  | 0.006060606060606061 	                         	|
+-----------+----------------------+----------------------------------------------------+
| chol(149) | 0.007246376811594203 | 0.006060606060606061                           	|
+-----------+----------------------+----------------------------------------------------+
| chol(157) | 0.0                  | 0.006060606060606061                          		|
+-----------+----------------------+----------------------------------------------------+

exercise 10 output:
Data shape: (3023, 5655)
Target shape: (3023,)
KNN Test accuracy (raw features): 0.23
X_train_pca.shape: (1387, 100)
KNN Test accuracy (PCA features): 0.29
DNN Test Accuracy: 0.40




