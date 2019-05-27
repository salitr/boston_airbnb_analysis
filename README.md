> Note: Due to the size of the .ipynb file, when running the file through Github, it will state "Limited rendering only, external view available with nbviewer." That is, you need to view the file through nbviewer available in the file (top right) to display the entire analysis with every single plot and map. 

# Boston Airbnb Analysis

The analysis shows how Airbnb is utilized in Boston, MA. I have analyzed Boston Airbnb listings from February 2019 to February 2020. The dataset used in the analysis reports the listing activities of homestays in Boston. The dataset incorporates over 6150 property listings including but not limited to hosts info, prices, neighborhoods, amenities, cancellation policy, and reviews.

## Libraries
In addition to importing pandas, numpy, os, matplotlib and multiple sklearn models, all the plots applied in the analysis requires the installation of plotly and cufflinks for interactive plots, and gmaps for mapping.

In case there is an error while importing cufflinks `ModuleNotFoundError: No module named 'cufflinks'`, we need to add the below command in Terminal to download cufflinks. [source](https://medium.com/@hicraigchen/plotly-with-pandas-via-cufflinks-in-jupyter-lab-issues-50fcf1a89a1c)

`pip install git+git://github.com/santosjorge/cufflinks.git#egg=cufflinks -U`

## Motivation
The analysis and its findings are only observational and not the result of a formal study. General business questions are listed below to guide us through the analysis to create a model that can predict the rental price based on some features.
1. How prices for all Boston's Airbnb fluctuate throughout the year 2019? 
2. What are the peak/off-peak times for Airbnb rental prices in Boston?
3. Who are the hosts with the most number of Airbnb listings?
4. Which neighborhoods have the most number of listing in Boston?
5. Which are the most expensive neighborhoods in Boston?
6. Which are the popular neighborhoods based on the avg number of reviews
7. Which type of room has the majority of listings in Boston Airbnb?
8. What are the features that influence the price in Boston Airbnb? Can we predict the rental price of new listings based on a predictive model?

## File Descriptions
1. Boston Airbnb data includes 3 files: *can be downloaded be clicking the file name*

  * [**listings.csv**](http://data.insideairbnb.com/united-states/ma/boston/2019-02-09/data/listings.csv.gz) Detailed Listings data for Boston. Date Compiled: 09 February, 2019
  * [**calendar.csv**](http://data.insideairbnb.com/united-states/ma/boston/2019-02-09/data/calendar.csv.gz) Detailed Calendar Data for listings in Boston. Date Compiled: 09 February, 2019
  * [**reviews.csv**](http://data.insideairbnb.com/united-states/ma/boston/2019-02-09/data/reviews.csv.gz) Detailed Review Data for listings in Boston. Date Compiled: 09 February, 2019

2. **boston_airbnb_analysis.ipynb** A copy of the notebook with a complete code cells
3. **boston_airbnb_analysis.html** An HTML export of the above analysis notebook

## Results
My post in Medium summarizes the main findings of the analysis.
  * [**Boston Airbnb Analysis**](https://medium.com/@salitr/boston-airbnb-analysis-f46bcda1713a)

## Licensing and Acknowledgement
The datasets used in this analysis were acquired from Inside Airbnb database under a Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license.

plotly provides examples of codes for different types of plots of which some have been adapted, edited, and used as needed. 
