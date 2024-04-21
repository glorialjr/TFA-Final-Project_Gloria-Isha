# TFA-Final-Project_Gloria-Isha <br>
Final project for IEOR E4501 Tools for Analytics. <br>

**Creators**: Gloria Li/jl6554 & Isha Yadav/iy2196 <br>

**Project Overview** <br>

**Problem statement**: Let’s say your NYC apartment lease is ending at the end of the year, and you need to find a new apartment. There are a lot of criteria you can use to help find a neighborhood you’d like to live in. One thing you care a lot about is a quiet neighborhood with a lot of greenery.<br>

**What this project does**: We used NYC Open Data datasets and Zillow’s historic monthly rent averages to create a single Jupyter notebook to download, clean, and store data, as well as defining a set of SQL queries and visualizations to help answer questions of yours in search of a great area to live within your budget. <br>

**Project Structure**: Our code is compartmentlized into four parts, including <br>
_Part 1 - Data processing_: We manually downloaded Zillow's historic rent dataset, NYC zipcode shapefile, and accessed the "311 Service Requests from 2010 to Present" and "2015 Street Tree Census - Tree Data" from NYC Open Data using an App Token. With the 4 datasets, we cleaned and filtered for the relevant data, filled in missing data, and generated samples of these datasets. <br>
_Part 2 - Data sorting_: We took the datasets downloaded & cleaned from Part 1, and populated a PostgreSQL database with tables generated from the datasets. <br>
_Part 3 - Data interpretation_: We crafted a set of SQL queries to develop a better understanding of the datasets we’re working with, addressing some of the important criteria a user considers when using our code to find a neighborhood to live in. <br>
_Part 4 - Data visualization_: We created visualizations to enhance the understanding of the datasets.  <br>
