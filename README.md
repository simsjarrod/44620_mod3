# Matplotlib and pyplot

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

Each question is worth two points: 

* Data plotted as described by the question (1 pt)
* Plot contains required elements (title, axis labels, axis titles, legend if required)

## Objectives
This exercise is used to reinforce key Python visualization skills. It offers practice with web-enabled Jupyter notebooks and lays some important foundations for presenting information obtained from mining the web and processing language.  We'll use the MatplotlibLinks to an external site. library. The Matplotlib library includes the pyplot module which provides a simple interface for building charts. All this code is free - the more you explore, the more you can do. Your skills are limited only by the time you wish to invest. 

Anytime we use an external library (something not included in the Python Standard Library) like Matplotlib,  we'll need to:

install it into our active virtual environment and
use an import statement in our Python. 
Spelling and capitalization matters - to use a library, you might need to first search for the install commands and then find the typical way it is imported into Python. The typical approach is to:

Create a virtual environment
Activate the virtual environment
Install into the active virtual environment (e.g. `python -m pip install matplotlib`)
In your Python, import it (e.g. `import matplotlib.pyplot as plt`)

## Module 3: Overview
Visualizations are an incredibly powerful tool in a Data Analyst's tool belt.  We use visualizations to condense information and make incomprehensible data tell a story to an audience.  Sometimes, that audience is a boss or stakeholder who wants a high level (non-technical) view of the information as it stands.  At times we are our own audience, using visualizations to explore data and find patterns we might not see directly in numerical or text data.  Whatever the purpose, the visualization must be appropriate to the audience, and tell the story that the data is trying to convey in an honest, easily digestible form.

While exceptionally high quality visualization tools like D3.js exist, and it is possible to embed D3 visualizations in a Jupyter NotebookLinks to an external site., we will focus on using a native Python tool to create both exploratory and high quality "finished product" visualizations for our data.

There is no "one size fits all" visualization for all data; in this module you will be introduced to matplotlib, practice some basic visualizations, and be exposed to documentation and tutorials that can help you create most any visualization you may need.

Read the following early in the week to help you complete your assignments.

* datavis_basics.pdf (https://nwmissouri.instructure.com/courses/53238/files/7687760?wrap=1)

Read and listen to the online lecture material on the following topics. 

* Read the Matplotlib Usage GuideLinks (https://matplotlib.org/stable/tutorials/introductory/usage.html). (stop at "Backends") and execute the sample code in a Jupyter Notebook.  If you are missing any modules, make sure you install them!
* Read the Pyplot tutorial (https://matplotlib.org/stable/tutorials/introductory/pyplot.html#sphx-glr-tutorials-introductory-pyplot-py) and work through the examples in a Jupyter Notebook
* Read and work through the Lifecycle of a PlotLinks to an external site.
* Be aware of the list of Sample Plots in Matplotlib (https://matplotlib.org/stable/gallery/indexLinks) these can be helpful when generating visualizations or drawing images you have not in the past.
* Read how to Manipulate the DOM in a Jupyter Notebook (https://medium.com/@stallonejacob/d3-in-juypter-notebook-685d6dca75c8) to embed visualizations using D3.js