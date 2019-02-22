# gpi-tl-networkAnalysis
A proof-of-concept to use social media data (e.g. twitter) to create network graphs.

## Setup of jupyter
The simplest way of setting up jupyter and a functioning Python installation on __Windows and Mac__ is `Anaconda`: https://www.anaconda.com/distribution/

Download the `Python 3.7` version. There is also a download for Linux, but I personally (as a Linux user) would recommend using your Linux distribution's built-in package manager to install all the necessary packages and versions, because `Anaconda` comes with it's own package manager, `conda`, which is again different from Python's own package manager, `pip`. So to avoid confusion about installed packages and versions, just stick to one.

Once everything is installed, you should be able to either open the jupyter Notebook from your applications or from the command line with `$ jupyter notebook`, which should open a new tab or browser window in your default browser. 

## Package versions 
Packages like `numpy` are required by `pandas` anyway and will be installed as dependencies.

| package 		  | version   |
|:-----------------------:| ---------:|
| `pandas` 		  | 0.23.4    |
| `plotly` 		  | 3.2.1     |
| `networkx` 		  | 2.2       |
| `matplotlib` 		  | 3.0.2     |
| `python` 		  | >=3.6     |

## jupyter in Google DataLab
For a quick start on how to use `jupyter notebooks` in the Google Cloud Platform, follow this link: https://cloud.google.com/datalab/docs/quickstart

## Further reading on Python and documentations for the used packages

#### Python Guide(s)
The documentation of Python is extensive and well made, so that is always a good place to start: https://docs.python.org/3/tutorial/index.html

You can find a lot of different tutorials online just by searching for a combination of the words `Python`, `data science`, `quick`, `tutorial`, e.g. the first search result for me was this (even tho it's from 2016): https://www.analyticsvidhya.com/blog/2016/01/complete-tutorial-learn-data-science-python-scratch-2/

But bear in mind that Python is NOT just used for data science, but is a fully fledged programming languages, and you might miss out on many power- and helpful features if you just stick to data science tutorials. 

#### plotly
Plotly provides a very neat interface for creating interactive plots, that base internally on JavaScript. You don't need to create an account and use their cloud functionality (there is the `plotly.offline` module as used in the notebooks in this repository). Have a look at their Gallery and documentation as well: https://plot.ly/python/

#### networkx
`networkx` is the backbone package for this repo, because it provides the functionality to create the network graphs we're interested in. This package provides a huge toolset of graph theoretical methods, so a read on their documentation is definitely not wasted time: https://networkx.github.io/documentation/stable/tutorial.html

#### pandas
`pandas` makes interfacing with datasets very easy, and provides many methods to transform and analyse the data. There is a package called `pandas-gbq`, that let's you query google BigQuery easily as well (not used in this repo though). And of course the link to the documentation: https://pandas.pydata.org/pandas-docs/stable/ 