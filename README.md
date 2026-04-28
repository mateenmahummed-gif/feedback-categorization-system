Feedback Categorisation Using Machine Learning
Student Details
Name: Mohammed Mateen
Roll No: 25WU0202058
**Project Type: Capstone Project
**Project Name: Feedback Categorisation Using Machine Learning
What This Project Does
This project takes customer feedback and predicts what type of feedback it is.

Example:

delivery was very late -> Delivery Issue
great product quality -> Positive
customer service was rude -> Service Issue
This is useful because companies get many reviews. Reading every review one by one takes time.
This model helps arrange feedback into clear categories.

Categories Used
The project uses these feedback categories:

Positive
Product Issue
Delivery Issue
Service Issue
Pricing Issue
Neutral
Where The Data Came From
First, a small sample dataset was created directly in Google Colab.

After that, a bigger CSV file named data set reviews.csv was uploaded into Colab.
The CSV file had customer feedback and the correct category for each feedback.

The uploaded file first had one combined column called:

feedback,category

That column was split into two separate columns:

feedback
category
Tools And Libraries Used
Python
Pandas
NLTK
Scikit-learn
TF-IDF Vectorizer
Logistic Regression
Matplotlib and Seaborn for graphs
HTML, CSS, and JavaScript for the website
Simple Explanation Of The Model
The model does not understand English like humans.
So the text is changed into numbers before training.

The main steps are:

Load the feedback data.
Clean the text.
Remove unwanted symbols and common words.
Convert words into numbers using TF-IDF.
Train the Logistic Regression model.
Test the model.
Show accuracy, report, charts, and sample predictions.
What Is Text Cleaning?
Text cleaning means making feedback easier for the model to read.

Example:

Original feedback:

The service was excellent and fast

Cleaned feedback:

service excellent fast

The model works better when extra words and symbols are removed.

What Is TF-IDF?
TF-IDF is a method that gives importance to useful words.

For example:

Words like delivery, late, and shipping can point to Delivery Issue.
Words like price, cost, and expensive can point to Pricing Issue.
Words like great, excellent, and amazing can point to Positive feedback.
What Is Logistic Regression?
Logistic Regression is a machine learning algorithm.
In this project, it learns patterns from feedback text and predicts the category.

Result
The model accuracy shown in Colab was around:

0.59

This means the model gave correct predictions for about 59% of the test data.

The accuracy can improve if we use:

more feedback data
cleaner categories
better balanced dataset
advanced models
What The Website Shows
The website presents the full project in a more attractive way.

It includes:

first page with student name, roll number, and capstone title
project overview
dataset explanation
model workflow
simple explanation of TF-IDF and Logistic Regression
classification report
confusion matrix
interactive bar and pie chart
important feedback words
live feedback prediction demo
project conclusion
Important Note About The Website Demo
The website demo is made using JavaScript so it can run in any browser.
It follows the same idea as the Colab model, but it is not directly running the Python model.

The real machine learning training was done in Google Colab.
The website is for presenting the project clearly and attractively.

Website File
The main website file is index.html.

