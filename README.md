# Wrangling Data in Python with Pandas
This is an archive for the materials for the *Wrangling Data in Python with Pandas* workshop series developed for and taught by the [Data Services department](https://uoregon.libcal.com/calendar/dataservices/?cid=11979&t=d&d=0000-00-00&cal=11979&inc=0) of the University of Oregon Libraries. 

This workshop series is taught once per trimester.

## Course Description
In this workshop, participants will learn to clean, analyze, and visualize tabular data with the popular package Pandas by working through hands-on exercises with real data in Python.

Topics covered include:
* Reading data in Python from multiple input formats
* Data cleaning and standardization
* Aggregating and transforming data
* Data visualization

## Prerequisites
No prior exposure to Pandas required! However, participants will be expected to understand variables, data types, conditional statements, modules, and functions in Python. 

Data Services offers a free [**Introduction to Python**](https://uoregon.libcal.com/calendar/dataservices?cid=11979&t=d&d=0000-00-00&cal=11979,11173,6522,3731&ct=71947&inc=0) workshop at Knight Library in the first month of every regular trimester, based on the [**Plotting and Programming in Python**](https://swcarpentry.github.io/python-novice-gapminder/aio.html) curriculum from Software Carpentry. Feel free to skim the lesson to refresh your Python knowledge.

I would also consider the following UO classes appropriate preparation:
* **DSCI 101**: Foundations of Data Science I
* **CS 122**: Introduction to Programming and Problem Solving

## Repository Structure
* `Archive/`
    - Materials for past sessions of the class. This workshop series has been taught under different names with a similar curriculum each time.
* `Notebooks`
    - Completed Jupyter notebooks uploaded after each class session for the current session.
* `Slides/`
    - Slides presented during lecture portions, updated after each session.
* `resources.md`
    - A list of data citations for in-class exercises.

## Activity Setup
Install Anaconda to your local machine.

Clone this repository to your computer.

Create a local conda environment with Jupyter and Pandas >= 2.23 installed. *This step is optional if you have an appropriate conda environment already.*

```bash
conda env create -f environment.yml
```

Activate the conda environment.
```bash
conda activate pandas-ws
```
Navigate to the `pandas-workshop` directory.
```
cd pandas-workshop
```
Launch JupyterLab from within the `pandas-workshop` directory.
```bash
juptyer lab
```

## Related Workshops
* [Python Data Wrangling](https://github.com/dlab-berkeley/Python-Data-Wrangling) — Berkeley D-Lab
* [Programming in Python for Data Science](https://prog-learn.mds.ubc.ca/eng) — University of British Columbia, Master of Data Science Program

## Data Services Resources
* [UO Data Services](https://library.uoregon.edu/data-services)
* [Data Services Python Consultations](https://uoregon.libcal.com/appointments/data_services)

## Contact
Questions? Suggestions? I can be reached by [email](https://library.uoregon.edu/directory/winter).