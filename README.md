
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project uses Python 3, along with Jupyter Notebook. The following libraries are necessary for running the notebook:
* Pandas
* Numpy
* MatplotLib
* Seaborn
* Scikit-Learn

Packages used by this project can also be installed as a Conda Environment using the provided Requirements.txt file.

## Project Motivation<a name="motivation"></a>

For this project, I was interested in exploring the Starbucks dataset to better understand the following questions:
1. How does Gender influence how much someone spends at Starbucks? Do men spend more than women, or the other way around?
2. How many people view and complete offers? And how many people complete offers without opening them first?
3. What are the attributes that most contribute to someone’s spending habits at Starbucks?


## File Descriptions <a name="files"></a>

The main code for this project is included in the notebook `Starbucks_Capstone_notebook.ipynb`. The notebook walks through all the steps of the CRISP-DM Process for analyzing the dataset to answer the above three questions. The code and results are also posted on Medium as a [blog post](https://medium.com/@ravishchawla/how-much-do-you-spend-at-starbucks-4f142138924a).

Data for the project is included because of small file sizes. To properly run the notebook, they must be kept in the same locations at `data`. The directory should have the following files:
* `transcript.json`
* `profile.json`
* `portfolio.json`

## Results<a name="results"></a>

In our Data Analysis, we answered the three questions that we set out to explore with the Starbucks Transactions dataset.

- Gender does influence how much a person spends at Starbucks. While Men tend to have more purchases, **Women tend to make more expensive purchases**. On average, women spend around **$6 more** per purchase at Starbucks.

- A significant portion of members do view and complete offers at Starbucks. Based on the dataset, **25%** of individuals actually receive, view, and complete the offers by making purchases associated with the offer. Furthermore, **10%** of individuals complete offers without actually viewing them first, completing them unintentionally.

- The attributes that most contribute to how much someone spends at Starbucks are **Income** and **Age**. While there are other contributing factors, such as Gender (as we saw previously), Income is the highest influencer with over **55%** importance when trying to predict the price of a coffee.


More detailed findings can be found at the post available [here](https://medium.com/@ravishchawla/how-much-do-you-spend-at-starbucks-4f142138924a).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit to Starbucks for providing the data. You can find the Licensing for the data and other descriptive information from [Udacity](https://www.udacity.om). This code is free to use.
