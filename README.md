To run the program, first download ```training.1600000.processed.noemoticon.csv``` dataset from ```http://help.sentiment140.com/for-students/``` and place it in the same folder as ```Sentiment_Analysis_Enhanced_NBC.ipynb```. Now you will be able to run the program in Jupyter Notebook. 
I tried to add the package at the beginning of the program. If you already have them installed in your computer, you can ignore those steps. 
- The first part of this project is loading the data and preprocessing the data. You can adjust the number of dataset you want to test in this part. The dataset will be shuffled to increase randomness. I seperated the dataset into 80% training and 20% testing for both models. 
- The second part is running the regular NBC model from ScikitLearn. I used CountVectorizer to tokenize my labels and it is taking a lot of computation powers. My computer can not handle dataset larger 30k. 
- The third part is my enhanced NBC implementation which includes preparing, validating and evaluating parts. I am handling tokenization in a for loop so it can take care of the entire dataset. 
- The fourth part is my repost.
