# Blog_FoliumMaps

> The accompanying blogpost which walks through this github repository can be found on [dev.to](https://dev.to/lberlin/folium-powerful-mapping-tool-for-absolute-beginners-1m5h)

My blog post on Folium is intended for complete newbies to data science, programming in Python, and data visualization. It assumes some basic knowledge of Python. The end result is a map of housing data, which displays popup details and which gives further details through the size and color of each dot.

Personally, I use [Anaconda](https://www.anaconda.com/) to manage my platforms, and do most of my coding in a [Jupyter Notebook](https://jupyter.org/).

The point of using Folium to visualize data is to improve upon [matplotlib's basemap](https://matplotlib.org/basemap/), to present an interactive (and much more visually appealing) map of your data.

![Comparison map - matplotlib's basemap vs Folium](/ComparisonMap.jpeg)

Follow along with the step-by-step creation of several iterations of the above map in the FoliumMapExamples.ipynb file. The associated dataset can be found at [https://www.kaggle.com/gabriellima/house-sales-in-king-county-usa/data](https://www.kaggle.com/gabriellima/house-sales-in-king-county-usa/data). 

-----

## Install Folium

```sh
$ pip install folium
```

or

```
$ conda install folium -c conda-forge
```

View the documentation for Folium [here](https://python-visualization.github.io/folium/index.html).

I also use the Python [Pandas data analysis library](https://pandas.pydata.org/) to read in and work with my dataset.

-----

## Meta

Please feel free to reach out with a comment on the associated blog post on [dev.to](https://dev.to/lberlin/folium-powerful-mapping-tool-for-absolute-beginners-1m5h) if you have any questions, comments or concerns!