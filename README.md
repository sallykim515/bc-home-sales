# bc-home-sales
A python program that scrapes a real estate search website, https://rew.ca, based on user-specified input and creates an interactive color-coded web map. 

# Getting Started
First, open the terminal and `cd` into the directory where you would like to download this program.
Then, clone the bc-home-sales repository
```
git clone https://github.com/sallykim515/bc-home-sales.git
```
Use the following command to run the program:
```
python app.py
```
When prompted, enter desired responses.

# Input
* Number of Cities

For each City:

* City Name
* 2-Letter Province
* Max Price
* Min # of Beds
* Year built from

# Output
* csv file of the scraped data in `scraping` folder
* html file of the web map in `webmapping` folder
    * color-coded based on 33<sup>rd</sup> and 67<sup>th</sup> percentiles
    * pop-up pin with property info & link to its original post

# Example
The below is a screenshot of the terminal for searching for home sales in 3 cities with varying input values for each city:
<img width="692" alt="Screen Shot 2020-05-04 at 1 34 07 PM" src="https://user-images.githubusercontent.com/39283556/81013609-4961f980-8e10-11ea-872f-ef639c5d0570.png">

Sample output csv file:
<img width="1162" alt="Screen Shot 2020-05-04 at 2 08 53 PM" src="https://user-images.githubusercontent.com/39283556/81014134-2552e800-8e11-11ea-851a-b7b90ca8154f.png">

Sample output web map:
<img width="979" alt="Screen Shot 2020-05-04 at 2 13 27 PM" src="https://user-images.githubusercontent.com/39283556/81014336-85498e80-8e11-11ea-9682-76505baf9d28.png">
