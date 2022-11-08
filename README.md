# Neural_Network_Charity_Analysis
## Overview
### We are using features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
## Data preprocessing
### The columns that are not categorized as the "IS_SUCCESSFUL" category are the feature variables.
### The "IS_SUCCESSFUL" column would be known as the target variables.
![image](https://user-images.githubusercontent.com/89429991/200686686-320b3368-6ba1-489f-95c1-5f2c382da43f.png)

### No variables should be removed from the input data.
## Compiling, training, and evaluating
### The number of input features do not appear to be identified. There are 3 layers and 3 activation functions.
![image](https://user-images.githubusercontent.com/89429991/200686855-d92962b5-b60c-4316-9a67-473aa5947b5d.png)

### I believe I was able to achieve the intended performance because initially I was getting a memory error and my values were out of range. Once I edited my code, I received smaller values and my table size was greatly reduced.
### I changed the numerical values as well as changing my hidden node layers to 80 for the first layer and 30 for the second layer.
## Summary
### There are a total of over 11,000 parameters which is a big number and there were a few accuracy scores over 70%, which is a decent score. Including a table named "IS_NOT_SUCCESSFUL" would be a recommendation I would make because I think it is important to know which models were a success and which ones failed.
