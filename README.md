# Toxic-Comment-Classification
This ML project aims to classify a comment into either a Toxic or Non Toxic class.
I used the Multinomial Event Model Naive Bayes for text classification.

Required Modules
Flask
There are few NLTk modules for text pre-processing like punkt, stopwords, and wordnet.
A brief explanation of files
TCC_Model.ipynb file contains the code of the model.
model.pkl is the pickle file created using the pickle module to save the model.
app.py file is an API file that contains 1 endpoint '/', which accepts a comment and returns the class of the comment.
How to Run
To run this project navigate to the folder in the command line and run the command 'python app.py'
