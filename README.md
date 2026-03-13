# SGD-Classifier
## AIM:
To write a program to predict the type of species of the Iris flower using the SGD Classifier.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
Program to implement the prediction of iris species using SGD Classifier.
Developed by: Vimalesh kanna MK
RegisterNumber:  212225230303

/*
# Import required libraries
from sklearn import datasets
from sklearn.model_selection import train_test_split
from sklearn.linear_model import SGDClassifier
from sklearn.metrics import accuracy_score, classification_report
from sklearn.preprocessing import StandardScaler

# Load Iris dataset
iris = datasets.load_iris()

X = iris.data       # Features
y = iris.target     # Target labels

# Split dataset into training and testing sets
X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.3, random_state=42)

# Feature scaling (Important for SGD)
scaler = StandardScaler()
X_train = scaler.fit_transform(X_train)
X_test = scaler.transform(X_test)

# Create SGD Classifier
sgd = SGDClassifier(max_iter=1000, tol=1e-3, random_state=42)

# Train the model
sgd.fit(X_train, y_train)

# Predict
y_pred = sgd.predict(X_test)

# Evaluate the model
print("Accuracy:", accuracy_score(y_test, y_pred))
print("\nClassification Report:\n", classification_report(y_test, y_pred))  
*/
*/
```

## Output:
<img width="838" height="288" alt="image" src="https://github.com/user-attachments/assets/166eedf1-e66a-4355-a3f9-14c476a24e91" />



## Result:
Thus, the program to implement the prediction of the Iris species using SGD Classifier is written and verified using Python programming.
