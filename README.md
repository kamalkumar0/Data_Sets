# Student Pass/Fail Prediction Using Python

Hi there!  
This is a simple machine learning project I made. It predicts whether a student will pass or fail based on:

- How many hours they studied on their own
- How many tutorial videos they watched

I used a basic Linear Regression model from the `scikit-learn` library for this.

## 📊 About the Data
The data comes from a CSV file and has 3 columns:

1. Hours of self study  
2. Number of tutorials watched  
3. Result (0 = Fail, 1 = Pass)

The file is taken from a public GitHub link:  
[student-pass-fail-data.csv](https://raw.githubusercontent.com/sarwansingh/Python/master/ClassExamples/data/student-pass-fail-data.csv)

## 🛠 How It Works
- First, the data is loaded using pandas.
- Then I split it into input values (X) and the output result (Y).
- I trained a Linear Regression model using this data.
- Finally, the program takes input from the user and gives a prediction — whether the student will pass or fail.

## 🔃 Requirements
Before running, make sure these libraries are installed:
```
pip install pandas scikit-learn
```
## ▶️ How to Run
1. Open your terminal or command prompt
2. Run the Python file like this:
```
python student_pass_predictor.py
```
3. You’ll be asked to enter two numbers:
- Enter the number of hours self studied? 4  
- Enter the number of tutorials you Watched? 3

Then it will show something like:
Predicted Output (Pass=1, Fail=0): 0.76
### That means the student has a 76% chance of passing.


## 💡 Some Notes

* This project is for learning purposes.
* It uses Linear Regression which is actually better for predicting numbers, not categories like pass/fail. But it still works okay for this simple example.
* For more accurate results in future, you could try using **Logistic Regression**.

## 🙌 License
This is a free project — feel free to use or improve it. Just give credit if you want :)

