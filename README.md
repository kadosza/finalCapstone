## Project name: 
finalCapstone - Analysis of USArrests data using unsupervised learning (PCA)

## Table of content:
1. [ Project description ](#description)
2. [ Project components ](#components)
3. [ Local installation ](#installation)
4. [ Usage ](#usage)
5. [ Credits ](#credits)

<a name="description"></a>
## 1. Project description:
The dataset contains data on murder, assault and rape made per 100,000 residents as well as percent of the population living in urban areas for 50 states in the US in 1973. The aim of this report is to analyse how data samples cluster together and how each crime type relates to each state using PCA and clustering methods. 

<a name="components"></a>
## 2. The project contains the following analyses: 
* **Data pre-processing** 
* **Identifying principal components influencing data separation using PCA analysis**
* **Identifying best clustering method using k-means and hierarchical clustering**
* **Final data separation into clusters based on the most optimal parameters**
* **Explanation of relationships and final conclusions**  

<a name="installation"></a>
## 3. Local installation info: 
1. Download files from this repository: 
 - The project file  
 - The .csv data file
You can also clone the repository into a new directory by following steps [here](https://git-scm.com/docs/git-clone).
2. install Anaconda from [Anaconda](https://www.anaconda.com/).
3. install the following Python modules with pip:
* **NumPy, Pandas**
* **seaborn and matplotlib.pyplot** 
* **Scikit-Learn, pca, scipy**
4. launch the project file.

<a name="usage"></a>
## 4. Usage: 
Run each cell in the file from the top to see each step of the analysis.  how to scale, use principal component analysis and how to create models for unsupervised machine learning.
 The file runs through uploading, inspecting the data, preprocessing, checking for correlations, running a PCA on non-standardised data, standardising and running a PCA on the standardised data, producing dendrograms and K-means.
 
![Dendrogram](C:\Users\bdzie\byb_project\img.png?raw=true "Optional Title")

<a name="credits"></a>
## 5. Credits: 
Author: Barbara Domanska.
Thanks to HyperionDev https://www.hyperiondev.com/ that inspired me to build this project.
