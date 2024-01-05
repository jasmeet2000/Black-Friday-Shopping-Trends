# Black Friday Shopping Trends: EDA and Predictive Analysis

## Overview

This project involves predictive modeling of customer purchase behavior in a retail dataset, encompassing data preprocessing, exploratory data analysis, and the implementation of linear regression, decision tree, and random forest models for purchase amount prediction. The code is organized in a Jupyter Notebook (.ipynb) file, covering data processing, visualization, and machine learning aspects.


## Getting Started

To run Jupyter Notebook (.ipynb) files, you need the following:

1. Python Installation:

To run the code, make sure you have **Python** installed on your machine (*Python 3.7.0*). Then, you can install the required libraries, which are discussed below in the next section. 


2. Jupyter Notebook Installation:

Jupyter Notebook is often included when you install Python using Anaconda. If you don't have Anaconda, you can install Jupyter Notebook using pip:

``` bash
pip install notebook
```


3. Libraries and Dependencies:

Ensure that you have all the required libraries and dependencies installed. You can use the following command to install them if you haven't already (in terminal) :-

``` bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

or write one by one:-
``` bash
pip install pandas 
pip install numpy 
pip install matplotlib 
pip install seaborn 
pip install scikit-learn
```

Libraries Used:-

- **Matplotlib**: A 2D plotting library for creating static, animated, and interactive visualizations.

- **NumPy**: A library for numerical operations in Python.

- **Pandas**: A data manipulation library for handling and analyzing structured data.

- **Seaborn**: A statistical data visualization library based on Matplotlib.

- **scikit-learn**: A library for simple and efficient tools for predictive data analysis.

Note: This code contains code snippets for performing Exploratory Data Analysis (EDA) using Python. The code utilizes various data visualization libraries, including Matplotlib, NumPy, Pandas, Seaborn, and SciPy.


5. Download the Code Files:

Download the .ipynb files for Blackboard.


6. Start Jupyter Notebook:

Type the following command to start Jupyter Notebook:-

``` bash 
jupyter notebook
```

Or open the anaconda software and then click on 'Open Lab'. This will open the Jupyter Notebook in the http://localhost:8888/


7. Upload the Pyton code (.ipny File) and the Dataset (.csv file):

Load the Pyton code (.ipny File) and the Dataset (.csv file) by clicking on the upload file in the top left of the Jupyter Notebook.

8. Loading the Dataset:

The dataset file name is 'train.csv'. Make Sure you put that in the same directory otherwise you need to give the path of the CSV File. (or Open a terminal or command prompt and navigate to the directory where your .ipynb files are located using the cd command)

```python
# Load the training dataset
train_data = pd.read_csv('train.csv')
```

9. Open and Run the .ipynb File:

In the Jupyter Notebook interface, navigate to the directory where your .ipynb file is located. Click on the .ipynb file to open it. Run the code cells one by one or use the "Run All" option from the toolbar to execute all cells.
