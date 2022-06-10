# Web scraper for rankingthebrands.com

[](screenshot_rankingthebrands.png)

## Purpose

The purpose of this Jupyter notebook is to capture data from RankingTheBrands.com's "Best Global Brands" for the years 2007 - 2022.

To collect the data, we repeatedly visit the website for RankingTheBrands, for each year. Subsequently, we parse the data from the ranking table (as seen on the screenshot below).

The data is saved as a flattened CSV file, as well as an Excel file w/ yearly data in individual tabs.

## Installation instructions

(1) In the cloud Go to colab.google.com, and import this Notebook (.ipynb). Click on "Run". The output data will be stored on Google Colab.

(2) On local computer It is best to install Jupyter Notebook via the Anaconda distribution.

    Go to the https://www.anaconda.com/products/distribution link and install Anaconda on your computer.
    Place this file ([`webscraping_ranking_the_brands.ipynb`](webscraping_ranking_the_brands.ipynb) on your Desktop, or any other folder of your choice.
    Open Anaconda Navigator, and launch Jupyter Notebook (which launches in your browser).
    Go to the folder that you placed the webscraping_ranking_the_brands.ipynb file
    Run the code by clicking on Cell --> Run cells.

## Final data sets

The final data sets have been committed to this repository.

- [Excel file](rankingthebrands.xlsx)
- [CSV file](rankingthebrands.csv)
