# Telecom-Customers-Churn
### Algorithms and libraires used: 
- Exploratory Data Analysis: Performing detailed statistical analysis on the data using univariate, bivariate, and multivariate methods
- Training and testing Logistic regression, KNN, and Naive Bayes models on dataset
Building a model that will help to identify potential customers who have a higher probability to churn. This helps the company to understand the pinpoints and patterns of customer churn and increases the focus on strategizing Customer retention.
### DATA DESCRIPTION:
Each row represents a customer, each column contains customer’s attributes described on the column
Metadata. The data set includes information about:
- Customers who left within the last month – the column is called Churn (target)
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device
protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents
### PROJECT OBJECTIVE:
To Build a model that will help to identify the potential customers who have a higher probability to churn. This will help the company to understand the pinpoints and patterns of customer churn and will increase the focus on strategizing customer retention
## Insights from data
![image](https://user-images.githubusercontent.com/92087972/192000600-e27fcb8e-37f9-41d9-8993-a9c8bf82c0e2.png)
![image](https://user-images.githubusercontent.com/92087972/192000730-fab84572-6b08-41ea-89e9-61a3e2b0f5ab.png)
![image](https://user-images.githubusercontent.com/92087972/192001449-641040ec-b316-488c-9529-8d7c00b6d15d.png)
![image](https://user-images.githubusercontent.com/92087972/192001637-aaff983c-bc6f-4fec-a35f-03852be21540.png)

### A) Logistic Regression
Accuracy: 0.7928909952606635

![image](https://user-images.githubusercontent.com/92087972/192002110-785182a1-ee5d-4c54-9295-3be3e5d47544.png)
![image](https://user-images.githubusercontent.com/92087972/192001898-05f32698-eae3-4d69-93a5-d34416c5ec71.png)

accuracy: 0.7393364928909952

![image](https://user-images.githubusercontent.com/92087972/192002468-772b9218-009a-4fe9-8afc-6825e89113e3.png)
![image](https://user-images.githubusercontent.com/92087972/192002550-394c8e96-45c0-4cca-bd20-c3fe6000ca4a.png)

#### Accuracy for (k=19): 0.7597156398104266
![image](https://user-images.githubusercontent.com/92087972/192002813-ae6128fe-493d-4c55-9295-76b8c27ac9db.png)

#### Logistic Regression - accuracy: 0.7928909952606635
#### Naive Bayes model - accuracy: 0.7464454976303317
#### KNN with optimal K - accuracy: 0.7597156398104266

3 different classification models are made, the logistic regression model gives us the best accuracy score for training and testing.
Whereass KNN model gives the good accuarcy for the training but the accuracy is decreased for testing.

### Below message in Python shell is seen, which indicates that our App is now hosted at 
http://127.0.0.1:5000/ or localhost:5000

The run() method of Flask class runs the application on the local development server.

app.run()
Yay, our model is ready, let’s test our bot. The above given Python script is executed from Python shell.

### Go to Anaconda Prompt, and run the below query.

python app.py

* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
![image](https://user-images.githubusercontent.com/92087972/208325175-de9be58e-2d68-4db0-9d85-818cb0e7b497.png)
