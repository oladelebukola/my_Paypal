# Welcome to My Paypal
## Task
The Task was to build a fraud detection model that will identify fraudulent transactions and minimize the classification of legitimate transactions as fraudulent using the dataset provided.

## Description
I used the following functions on the dataset provided:
def load_dataset(): It read the data from a file('my_paypal_creditcard.csv')using a library-like pandas and returned the loaded DataFrame.
def print_summarize_dataset(dataset):it printed the summary statistics of the numerical variables  including count, mean, standard deviation, minimum, quartiles, maximum values, and any other relevant details like the number of rows and columns in the dataset
def clean_dataset(my_paypal_creditcard_dataframe):It is used to perform data cleaning and preprocessing operations on the dataset.
by taking the original DataFrame as input (my_paypal_creditcard_dataframe), performs the cleaning operations, and returns the cleaned DataFrame.
def print_histograms(dataset):It took the cleaned dataset as input and plots histograms for each variable/attribute providing insights into the distribution and range of values for each variable.
def visualize_class(dataset):It calculated the count of non-fraudulent and fraudulent transactions and created a bar plot to visualize the class distribution
class_weights = compute_class_weight('balanced', classes=np.unique(y_train), y=y_train):It returned an array of class weights, where each weight corresponds to a class label giving more importance to minority(Fraudulent) classes.
logreg = LogisticRegression():It model the relationship between the input variables and the binary target variable using logistic regression
rf = RandomForestClassifier():It trained the random forest model on the training data, make predictions on new data, and evaluate the model's performance.

## Installation
There was no need for any installation as it can be run on local machine using Jupyter notebook and other necessary dependencies

## Usage
The code was run on a jupyter notebook whose http address can be gotten by running this in the terminal:
jupyter notebook
then the jupyter address can be followed after inserting 'web' and the password 'qwasar' inputed
Run 'pip install -U scikit-learn' on the terminal

### The Core Team
Bukola Veronica Oladele(veronica_b)


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
