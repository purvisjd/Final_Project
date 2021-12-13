# Wine quality testing machine learning code

This code was used as part of a final project for a data analysis bootcamp in which the goal was to train a machine language model to predict quality scores for wine based on specific factors.  A direct breakdown of the code is included in the ipynb files themselves.  An additional "wine creator file" was created in order to generate a completely fresh data file for the trained model to generate scores for.

The data for this project has been split into two separate directories:  a dataset directory and a code directory.

## Data Sets
Two separate CSV files were used for this project.  The wine_training_data.csv file includes the initial dataset downloaded from Kaggle.  The winequality-sample-set.csv file is the sample wine file created using random number generator code to simulate a batch of wine created by the fictional winery.

## Jupyter Notebook Code
This folder contains three separate code files.  Machine_learning_model_tests includes samples of different learning models that were tested, but not used in the final production code.  The Wine Test File Creator code file is the python code that was used to create a fictional sample set that was then saved into a CSV file to be used in the final processing of the trained model.  The Machine Learning Code file is the production code that was used in the final project.  All files have internal documentation explaining the various steps used.
