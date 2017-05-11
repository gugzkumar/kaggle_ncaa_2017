# kaggle_ncaa_2017
A predictive model for the 2017 NCAA Basket Ball Tournament using data provided from Kaggle 

These are series of Notebooks that were created to turn from Kaggle's 2017 NCAA March Madness contest data into a predictive model for the contest.
https://www.kaggle.com/c/march-machine-learning-mania-2017

These are the Notebooks included:
`NCAAModelSetup2017.ipynb` Creates a dictionary of in box data for each team based of the data provided from Kaggle. It then saves the dictionary to the p file
`NCAAModelCreation2017.ipynb` Loads the dictionary created by the previous notebook and trains a Logistic Regression with it. It then creates a csv file that you can use as Kaggle submission
`NCAABracketExtraction.ipynb` reads a submission file and creates a bracket. It then follows along with the Tournament and shows what new brackets look based of previous upsets.

`model2007.py`, `statdict.py`, `Submission_2017.csv` are files created by the Notebooks
