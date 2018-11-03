# School-of-ai-2nd-meetup

Hello world, Here is the comprehensive list of all the inforamtion we discussed today in our meetup.

## What is [NumPy](https://docs.scipy.org/doc/numpy-1.13.0/user/whatisnumpy.html)
NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.

Read more about NumPy in the [documentation](https://docs.scipy.org/doc/numpy-1.13.0/user/whatisnumpy.html)

### Read the following documents  for concise information to what you need to know about NumPy

* [Intro to NumPy](/2ndMeetup-Resources/05-Markdown/01-IntroductionToNumpy.md) ([PDF](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/01-PDFs/01-IntroductionToNumpy.pdf))
* [Element Wise operation](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/05-Markdown/02-ElementWiseOperation.md) ([PDF](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/01-PDFs/02-ElementWiseOperation.pdf))
* [Matrix Multiplcation with NumPy](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/05-Markdown/04-NumPyMatrixMultiplication.md) ([PDF](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/01-PDFs/04-NumPyMatrixMultiplication.pdf))
* [Important reminders about Matrix Multiplcation](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/05-Markdown/03-MatrixMultiplication.md) ([PDF](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/01-PDFs/03-MatrixMultiplication.pdf))
* [Transpose in Matrix using NumPy](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/05-Markdown/05-Transpose.md) ([PDF](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/01-PDFs/05-Transpose.pdf))


### Try it out yourself

* [Basics of Numpy Array](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/01-PDFs/06-The_Basics_Of_NumPy_Arrays.pdf) ([Jupyter Notebook](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/Demo/The_Basics_Of_NumPy_Arrays.ipynb))
* [NumPy Quiz](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/07-Quizes/01-NumpyQuiz.ipynb)
* [Solution](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/08-Solution/01-NumpyQuiz-Sol.ipynb)
* [Free Udemy NumPy Course]((https://www.udemy.com/deep-learning-prerequisites-the-numpy-stack-in-python/))

## What is [pandas](http://pandas.pydata.org)

Pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

Pandas is a NumFOCUS sponsored project. This will help ensure the success of development of pandas as a world-class open-source project, and makes it possible to donate to the project.

Read more about Pandas in the [documentation](http://pandas.pydata.org)

The following set of notebooks should help you learn pandas in detail. [Source](https://github.com/jvns/pandas-cookbook/tree/v0.2)
* [Chapter 1 - Reading from a CSV](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/Demo/Pandas/Notebooks/Chapter%201%20-%20Reading%20from%20a%20CSV.ipynb)
* [Chapter 2 - Selecting data & finding the most common complaint type](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/Demo/Pandas/Notebooks/Chapter%202%20-%20Selecting%20data%20%26%20finding%20the%20most%20common%20complaint%20type.ipynb)
* [Chapter 3 - Which borough has the most noise complaints (or, more selecting data)](http://tiny.cc/k6fp0y)
* [Chapter 4 - Find out on which weekday people bike the most with groupby and aggregate](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/Demo/Pandas/Notebooks/Chapter%204%20-%20Find%20out%20on%20which%20weekday%20people%20bike%20the%20most%20with%20groupby%20and%20aggregate.ipynb)
* [Chapter 5 - String Operations- Which month was the snowiest](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/Demo/Pandas/Notebooks/Chapter%206%20-%20String%20Operations-%20Which%20month%20was%20the%20snowiest.ipynb)
* [Chapter 6 - Cleaning up messy data](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/Demo/Pandas/Notebooks/Chapter%207%20-%20Cleaning%20up%20messy%20data.ipynb)
* [Chapter 7 - How to deal with timestamps](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/Demo/Pandas/Notebooks/Chapter%208%20-%20How%20to%20deal%20with%20timestamps.ipynb)
* [Chapter 8 - Loading data from SQL databases](https://github.com/jubeenshah/School-of-ai-2nd-meetup/blob/master/2ndMeetup-Resources/Demo/Pandas/Notebooks/Chapter%209%20-%20Loading%20data%20from%20SQL%20databases.ipynb)

The goal of the following cookbook is to give you some concrete examples forgetting started with pandas. The [docs](http://pandas.pydata.org/pandas-docs/stable/) are really comprehensive. However, I've often had people tell me that they have some trouble getting started, so these are
examples with real-world data, and all the bugs and weirdness
that that entails.

### How to use these notebooks

```
pip install ipython pandas numpy tornado pyzmq jinja2 matplotlib
```

Or better yet, while in conda environment use the `conda` command to install the dependencies.

Create a new environment 
```
conda create -name pandasEnv
conda activate pandasEnv
```
Or go to the console and select, open with terminal and run the following command.

```
conda install ipython pandas numpy tornado pyzmq jinja2 matplotlib python=2.7 notebook jupyter jupyterlab_launcher jupyterlab
```










