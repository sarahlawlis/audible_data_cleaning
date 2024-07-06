# Audible Data Cleaning
The purpose of this project is to clean a dataset containing data from Audible. The clean data is intended for data visualization use in Tableau.

## Getting started
1. [Download and install Visual Studio Code](https://code.visualstudio.com/download) on your machine
2. Open Visual Studio Code and then choose the folder you want to work in. If you are not sure how to choose this, just create a folder in whichever location you want this project to live on your computer! For example, my project is in my TA folder on my Desktop
3. Open the terminal using ctrl ` on your keyboard
4. Clone the audible_data_cleaning repository by using the command git clone https://github.com/sarahlawlis/audible_data_cleaning.git
5. Set up a python virtual environment in the folder you chose in step 2. You can do this by running the command python -m venv env. Note that the "env" part of that command can be exchanged for any name you want for your environement
6. Activate your virtual environment by running the command source ./env/bin/activate
7. Install your dependencies (python libraries we will use in this project) by running pip install pandas, and pip install numpy
8. Open the data_cleaning.ipynb file from the Explorer tab and select your kernel (button in the top right), you should choose the python environment you just made as your environment
9. You may need to install extensions including python and jupyter which Visual Studio Code should prompt you to do
10. Change file paths in the notebook to point to your local machine
11. Run the code!

## Files
* audible_start.xlsx - excel file containing the original data
    - fields: ID, name, author, narrator, time, releasedate, language, stars, price
* data_cleaning.ipynb - jupyter notebook that loads, cleans, and exports the data back to an excel file
* audible_clean.xlsx - the excel file output from the jupyter notebook containing the clean data
    - fields: ID, name, author, releasedate, language, price, minutes, star_rating, ratings_count

## Python libararies used
* [Pandas](https://pandas.pydata.org/) - a Python library used for manipulating data and performing analyses
    - functions used: read_excel, drop_duplicates, dropna, astype, replace, extract, fillna, drop, to_datetime, contains, apply, to_numeric, to_excel
* [Numpy](https://numpy.org/) - a Python libaray that supports array and matrix operations as well as mathematical functions

## Authors
Sarah Lawlis - [GitHub](https://github.com/sarahlawlis) - [LinkedIn](www.linkedin.com/in/sarah-lawlis)
