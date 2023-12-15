# D7041E Mini Project
### Jenny Sundström and Elvira Forslund Widenroth Group 9
### ejyuso-2@student.ltu.se elvfor-0@student.ltu.se

Our chosen Mini project for course D7041E was to build a multiclass classification neural network model. This was done with inspiration from the following example: https://machinelearningmastery.com/building-a-multiclass-classification-model-in-pytorch/ together with the wine dataset https://archive.ics.uci.edu/dataset/109/wine 

## Nested k-folds cross validation explained

https://www.baeldung.com/cs/k-fold-cross-validation

![image](https://github.com/jennysundstroem/D7041E_mini_project/assets/94536008/a100233c-8067-455a-b0bb-efc06590d040)

## Running the code

The project is written in Jupyter Notebook and this needs to be installed to run the code as is. Here is the installation guide for Jupyter Notebook: https://jupyter.org/install
When all the installations are completed you should be able to simply run the code in Jupyter. 

## Installation for libraries needed to run our project:

pip install matplotlib
pip install numpy
pip install pandas
pip install torch
pip install scikit-learn
pip install tqdm

## Dataset

There is no need to download the dataset manually, it is collected by an import in the code. However it could be downloaded from here: https://archive.ics.uci.edu/dataset/109/wine

## Replicating the results

In order to replicate the results you simply run the code and have a look at the markdown cells that explains what the results should be. The final result of the tuned model should be around 90% and this is also documented in the last cell of the code.
