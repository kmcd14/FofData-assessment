#  <b>FUNDAMENTALS OF DATA ANALYSIS ASSESSMENT</b>

<br>

This respository contains Jupyter notebooks and other relevant files relating to the module assessment for Fundementals For Data Analysis.
 This `README.md` file contains the documentation for technologies and libraries used for the project. 


All notebooks and all other relevant files can be found at: https://github.com/kmcd14/FofData-assessment.


<br>
<h2 style=color:#DDA0DD><b><u>Table of Contents</b></u></h2></summary>
  <ol>
    <li><a href='#Description'> Description</a></li>
    <li><a href="#Script">How To Get The Respoistory on Your Machine</a></li>
    <li><a href="#Jupyter">Running Jupyter Notebook</a></li>
    <li><a href='#Technologies_Used'>Technologies Used</a></li>
    <li><a href="#Libraries_Used">Libraries Used</a></li>
    
  </ol>
  
---
---
<h2><b><u><p id='Description'> Description</b></u></p></h2>
<br>

The notebook `pyplot.ipynb` is in relation to the matplotlib.pyplot assessment for the module. 

The aim of this notebook is to provide a clear and concise overview of the Python package ```matplotlib.pyplot```. This will be achieved by reseaching the package and demonstrating it's functionality through a choice of three of the plots the package provides.

<br>

 <h4><u> Objectives: </u></h4>
 <ul>
  <li>Explain the overall purpose of the package.</li>
  <li>Explain the use of three plots the package contains. </li>
  <li>A clear and informative READMe file.</li>
  <li>A requirements.txt file.</li>
</ul>

<br>

I enjoyed undertaking this project as it enabled me to develop an appreciation for `matplotlib` and its capabilities. For example, up until this project I believed a plot to be the correct term but I now know about the anatomy of a figure. 

Images are a powerful form of communication and are an integral part of data analysis. 
It is important that we can visualise our data for others who may not be versed in data or programming so they can understand our findings. It is often easier to digest an image than blocks code or digits. Additionally, by visualising our data it allows us to see patterns that we may not have otherwise noticed.

<br>

In the future to futher exapand on this project and to continue my leaning and development, I would like to explore `matplotlib`'s object oriented interface. The `pyplot` module is a state machine interface. This means that the current figure is automatically created, updated and edited with method passed. This makes `pyplot` simple, easy and efficent to use.  Additionally,  `matplotlib` has an objected orientated interface. 
Using an object-oriented approach gives you total control of a figure and all the elements which it contains. method is to create figure objects and then call methods off of it. 

<br>

---

<br><br>
<h2><b><u><p id='Script'> How To Get The Respoistory on Your Machine</b></u></p></h2>

<ol>
<li>Open your teminal.</li>
<li>Naviagte to where you wish to create and store the folder. </li>
<li>Using your browser navigate to the repository:  

https://github.com/kmcd14/FofData-assessment. </il>



<img src='images/repository.PNG'>

<li>Copy the repository address, as seen in the above picture. Using either SSH or HTTPS</li>
<li>In the terminal - make sure you are in the folder where you wish to save the folder - type the command:



    $git clone git@github.com:kmcd14/FofData-assessment.git


</li>
<li>Set up pull mode and pull down the contents
</li>
</ol>

</br>

---

</br>

To access this notebook - numpy-random.ipynb -  you will need to install Python preferably through Anaconda distribution. 


<h3><b><u><p id='Jupyter'>Running Jupyter Notebook</p></b></u></p></h3>
  
  - From the command line navigate to the folder you have cloned the repository.
  - Type `jupyter lab`  or `jupyer notebook` into the command line and press enter.
  - Open the `pyplot.ipynb` notebook in the browser.
  - To run the code in a cell hold down the `shift key` and press `enter`.
  - To change between edit and read mode at any time press the `ESC key`.
  - When you have finished, shut down the kernal via file > shut down in the browser, close the browser and press Press `Ctrl + C` on the command line to terminate the programme.


<br>


<h3><b><u><p id='Technologies_Used'> Technologies Used:</b></u></p></h3>

<b><u>Google Docs:</u></b> an online word processor used to write my documentation before transfering into this README file. https://www.google.com/docs/about/

<b><u>Anaconda:</u></b> the easiest way to perfrom Python data science machine learning on Windows, Linux and Mac OS. This script was created using Version 4.9.2. https://www.anaconda.com/distribution/

<b><u>Python:</u></b> an interpreted, object-oriented, high-level programming language with dynamic semantics. This script was created using Version 3.8.5.  https://www.python.org/

<b><u>GitHub:</u></b> is a code hosting platform for collaboration and version control. https://github.com/

<b><u>Jupyter Lab/Jupyter Notebook:</u></b> a web-based interactive development environment for Jupyter notebooks, code, and data. https://jupyter.org/

---
---

<h3><b><u><p id='Libraries_Used'>Libraries Used:</b></u></p></h3>

<i>“Python is a widely-used, interpreted, object-oriented, and high-level programming language with dynamic semantics, used for general-purpose programming. It was created by Guido van Rossum, and first released on February 20, 1991”</i> (Python Institute, 2021). It is suitable for research, prototyping and building production systems, which eliminates the need for using different languages for both. Python has a vast and continuously growing library to choose from which makes it perfect for data analysis, such as Numpy and Pandas. It is a robust, flexible and efficient language which provides many solutions and avenues to approach and solve problems.

<u><b>Numpy</b></u> is a Python library used for working with arrays. It produces a narray object. Numpy arrays are faster and more efficient than using python lists. It does this by storing arrays in one place in memory, so they can be accessed and manipulated quickly http://www.numpy.org/

<u><b>Mathplotlib</b></u> is a python library used to create plots, graphs, charts etc. https://matplotlib.org/

<u><b>Pandas</b></u> is a data manipulation tool built on Numpy. It’s key structure is the dataframe. You can think of a dataframe as a spreadsheet or table but, dataframes as are more efficient and powerful and are an integral part of Python and Numpy. Pandas will allow us to select specific rows and columns within the dataframe. https://pandas.pydata.org/

<u><b>sklearn.datasets</b></u> This package also features helpers to fetch larger datasets commonly used by the machine learning community to benchmark algorithms on data that comes from the ‘real world’. https://scikit-learn.org/stable/datasets.html

<u><b>Seaborn</b></u> is based on matplotlib and is also used to create data visualisations. “It provides a high-level interface for drawing attractive and informative statistical graphics.” https://seaborn.pydata.org/


<b>If your system does not have these libaries installed enter the below command from the command line: </b>

```
    $pip install <library name>
```
---
---
