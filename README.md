# python-portfolio-project-biodiversity-analysis

This project performs several analyses of plant and animal data at four US National Parks. The data supplied is primarily categorical but with one column representing the number of periodic species observations. Exploratory data analysis (EDA) is conducted by looking at statistics using `.describe()` and then re-formatting the data with by grouping, pivoting, replacing and filling NaNs. Several data visualizations (bar plots) are included - `.plot()`, and seaborn's `.barplot()`. 
Contingency tables and marginal proportions are calculated to prepare for chi-squared testing, a statistical hypothesis test for which this data is particularly well suited.

One of the csv files contained the conservation status for a small number of relevant species. Therefore I used regex and merging, and looping and conditionals, to interpret and visualize data characteristics, and to look for correlations (of conservation status and observations) based on location.

The interactive notebook was created with Jupyter, Version: 7.0.3. Needed libraries include pandas, NumPy, seaborn & matplotlib, and SciPy.stats (for chi2_contingency). I also played around with matplotlib's style module, but I left it commented-out inside this ipynb.  

My purpose in creating and posting this project is to further develop my skills and increase my knowledge of the data science arts, particularly in the areas described above. I use 
[Codecademy](https://www.codecademy.com/catalog/language/python), its affiliated community and other forums for source data, feedback, and to review innovative approaches to coding. Codecademy has a wealth of worthy project ideas; it has served me well in my programming and data science journey.

The MIT License is used for this project.