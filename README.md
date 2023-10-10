# Titanic-Survived-Predict

This project originated from a Kaggle competition the goal is use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.
![image](https://github.com/this1shung/Titanic-Survived-Predict/assets/126255184/b6851a6d-3713-46fc-825f-8b570e47a8cc)

# Problem definition

- The purpose of the competition mentioned above is to predict whether passengers on the ship can survive the shipwreck or not, and when referring to whether or not, that is indeed a BINARY CLASSIFICATION problem

# Data

- The data for the project can be download right here https://www.kaggle.com/competitions/titanic/data

- We have two set of data, train.csv and test.csv that include passenger information like name, age, gender, socio-economic class, etc.

  +  The training set include the outcome(also known as the “ground truth”) for training purpose

  +  The test set not coming with the outcome because the mission of the model is predict the outcomes base on what it learn from the training set

- In this project I strongly focus on data manipulation :

  +  I have compared and plotted the relationships between independent variables as well as between independent variables and the dependent variable to gain a deeper understanding of the data and facilitate feature engineering

  + Feature engineering : I have created additional columns from derived information from the existing columns (after analysis and understanding of those columns), while also removing unnecessary columns that might affect the model. Furthermore, I have simplified the values and converted them into ordinal values    

- After all the operations, I have obtained the final two files for the test set and the train set, which have been uploaded along with the other files

# Feature

- The data dictionary is document inside the notebook

# Evaluation 

- In addition to accuracy, I have also used precision, recall, and F1 score, which are common metrics for evaluating models in binary classification problems.

# Model

- I have use four different models RandomForestClassifier, LogisticRegression, KNeighborsClassifier,DecisionTreeClassifier and then selected the model with the best scores on each metric to use as the final choice(use to predict on test set)

# Final

- This is just a summary of the project. All other information, work processes, and charts are available in the uploaded notebook.

- I still feel unsatisfied with the model's results after this project. If you have any methods or approaches that can help me improve the model please feel free to contact me. Your insights would be greatly appreciated

# Some picture of my work:
![image](https://github.com/this1shung/Titanic-Survived-Predict/assets/126255184/daf3b542-cf1f-49e9-bcb9-726485b43199)
![image](https://github.com/this1shung/Titanic-Survived-Predict/assets/126255184/e3f02b9b-74e1-445d-8b98-36346e68bb92)
![image](https://github.com/this1shung/Titanic-Survived-Predict/assets/126255184/f9dfc5fd-726b-46f5-9bca-3cac63945544)
![image](https://github.com/this1shung/Titanic-Survived-Predict/assets/126255184/30bbfbd2-afa2-4279-bd0c-c195d5cfd109)
![image](https://github.com/this1shung/Titanic-Survived-Predict/assets/126255184/76913f60-6510-4c47-b907-561327e0603e)
![image](https://github.com/this1shung/Titanic-Survived-Predict/assets/126255184/59acc4a1-a5b2-4697-9597-ca31bed25424)
![image](https://github.com/this1shung/Titanic-Survived-Predict/assets/126255184/33886809-7bbf-41d3-b02a-171f16dccef2)
![image](https://github.com/this1shung/Titanic-Survived-Predict/assets/126255184/c8e24ccd-cd55-414a-8b95-52f8ea8fab96)
![image](https://github.com/this1shung/Titanic-Survived-Predict/assets/126255184/8e297792-f97f-453d-b888-3e348b7daf25)

Thank you for reading my project details, Wishing you a great day!


## 📫 How to reach me: <a href="https://hungmondaypkm@gmail.com" target="blank"><img align="center" src="https://img.icons8.com/color/48/000000/gmail--v2.png" alt="hungmondaypkm@gmail.com" height="30" width="40" /></a><a href="https://www.facebook.com/profile.php?id=100009216758210" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="1" height="30" width="40" /></a><a href="https://twitter.com/gnuhmonday" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="1" height="30" width="40" /></a><a href="https://www.linkedin.com/in/quang-h%C6%B0ng-l%C3%AA-989610293/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="1" height="30" width="40" /></a>







