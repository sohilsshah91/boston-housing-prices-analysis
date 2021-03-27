# boston-housing-prices-analysis
Boston Housing Prices Analysis

PART-1: MOTIVATION OF THE PROJECT:
I am interested in learning about the patterns and trends in housing prices during COVID-19 pandemic.


PART-2: INTRODUCTION:
With the above motivation in mind, we will be focusing on the following questions:
1. Which locations are hot markets in terms of high number of listings in Boston, MA area?
2. Which are the most expensive neighborhoods (USD and USD/sq foot) in Boston, MA area?
3. How do housing prices vary across property types?
4. What type of impact do parameters like number of baths, beds, square feet or age of the plot have on the housing prices?  


PART-3: TECHNOLOGIES & INSTALLATION:

Technologies:
1. Python 3.6
2. Jupyter 4.9.2
------------------------------------------------------------

Libraries:
1. Data Manipulation: pandas, numpy
2. Data VIsualizaiton: matlitlib, seaborn
------------------------------------------------------------

Installation: (Reference: https://test-jupyter.readthedocs.io/en/latest/install.html)
1. Installing Jupyter using Anaconda and conda
For new users, we highly recommend installing Anaconda. Anaconda conveniently installs Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.
Use the following installation steps:
- Download Anaconda. We recommend downloading Anaconda’s latest Python 3 version (currently Python 3.5).
- Install the version of Anaconda which you downloaded, following the instructions on the download page.
- Congratulations, you have installed Jupyter Notebook. To run the notebook:

2. Alternative for experienced Python users: Installing Jupyter with pip
NOTE: Jupyter installation requires Python 3.3 or greater, or Python 2.7. IPython 1.x, which included the parts that later became Jupyter, was the last version to support Python 3.2 and 2.6.
As an existing Python user, you may wish to install Jupyter using Python’s package manager, pip, instead of Anaconda.
First, ensure that you have the latest pip; older versions may have trouble with some dependencies:

pip3 install --upgrade pip

Then install the Jupyter Notebook using:

pip3 install jupyter


PART-4 : STRUCTURE OF THE PROJECT:
For this project we have -- 1 code file: boston-housing-prices-analysis-notebook.ipynb
	                     -- 1 dataset : boston_housing_prices_analysis.csv                                                 
                    	 -- 1 readme file, where I have documented the required steps useful

You can also find the detailed analysis of this project on my blogpost: https://sohilshah-83563.medium.com/boston-housing-prices-trend-analysis-part-1-eca95932316b


PART-5: SUMMARY OF ANALYSIS:
1. Which locations are hot markets in terms of high number of listings in Boston, MA area?
-  Areas close to downtown Boston city like Boston, South Boston and South End have more number of listings justifying the popularity of the Boston city's neighborhood.

2. Which are the most expensive neighborhoods (USD and USD/sq foot) in Boston, MA area?
-  Some of the neighborhoods like Beacon Hill and Back Bay that are in popular hot listings do also fall into the list of the most expensive localities in Boston.
-  Most of the popular locations by count of listings are not a part of top pricey locations list in Boston area.

3. How do housing prices vary across property types?
-  Condos/ Co-ops have most of the listings in the current data set. However, they have relatively lower average prices compared to family residential listings.
 

4. What type of impact do parameters like number of baths, beds or square feet of the plot have on the housing prices?
-  The average pricing does not vary much with number of baths overall.
-  Pricing is variedly distributed for Condos for the higher number of baths (number of baths greater than 3)
-  Pricing is mostly on the lower end but have high range of the number of rooms.
-  Pricing is variedly distributed for Condos with respect to number of beds. Condos generally do not have higher number of beds relatively.
-  Pricing is variedly distributed for Condos with respect to square feet. Condos generally do not have higher number of beds relatively.


PART-6: ACKNOWLEDGEMENTS:
This dataset has been taken from Redfin's website, link is: https://www.redfin.com
I would also like to thank Udacity Data Science Nanodegree program mentors for the motivation, support and guidance.