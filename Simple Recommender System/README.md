
# Project: Simple Recommender System with Python

In this notebook we will develop basic recommendation systems in Python using pandas.

It provides a basic recommendation system by suggesting items that are most similar to a particular item, in this case, movies. Keep in mind, this is not a true robust recommendation system, to describe it more accurately,it just tells you what movies/items are most similar to your movie choice.
Let's get started!

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 


### Run

In a terminal or command window, navigate to the top-level project directory `Simple Recommender System /` (that contains this README) and run one of the following commands:

```bash
ipython notebook Simple_recommender_system.ipynb
```  
or
```bash
jupyter notebook Simple_recommender_system.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.


### Data

**Features**
1.  `user_id`: Unique identifier for a user.
2. `item_id`: Unique identifier for a movie.
3. `rating`: Rating given by users.
4. `timestamp`: Time of the release.
5. `title`: Title.