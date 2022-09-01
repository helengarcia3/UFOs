# UFOs


## Overview

### Purpose

The purpose of this analysis is to help Dana visualize and analyze the data she has of UFO sightings in US & Canada. We will be using Java script to visualize the data and filter through the date, location and duration of the sightings as well as the shape of the object observed.

The code has been updated to filter the table for the city, state, country, and shape. These filters can help narrow down the search to specific time and place.

## Results

### The Webpage

The website created for this analysis is below. There is an over view, a table and search filter. 

![Screen Shot 2022-08-31 at 9 29 33 PM](https://user-images.githubusercontent.com/107590196/187815179-fbc8127b-aaaf-40e6-b39e-ccaf2c409878.png)


In order to use the webpage we created via JavaScript to filter through the table, we will use the 'Filter Search' on the bottom left hand side and enter the search criteria in the white boxes shown below.

<img width="361" alt="Screen Shot 2022-08-31 at 9 55 58 PM" src="https://user-images.githubusercontent.com/107590196/187815845-ff7e2d45-f3e7-4b57-b28b-3bd915035ae0.png">

### Example Search

Below we are searching for UFO sightings in California and narrowed down to San Diego sightings on 1/1/2010. AS shown below there are 2 occurrences that match this criteria. 

![Screen Shot 2022-08-31 at 9 31 08 PM](https://user-images.githubusercontent.com/107590196/187815167-14bdf565-402b-4fbe-850a-6da2e9328123.png)




## Summary

The webpage created for the filter is pretty straight forward and easy to use but many things can go wrong when conducting a search. The major drawback is that it with the blank boxes to use to filter is that if a typo occurs in the search criteria there will be no results found. 

To resolve this issue I would recommend that the country, state, city, and shape become drop down so we can select from the options given when you begin typing. This will ensure that a typo can be eliminated. 

ANother solution for this is for the date format be more flexible. If someone searches MM/DD/YYYY like the search below, there will be 0 results even though there are many occurrences on this date as shown in the picture below.
<img width="1407" alt="Screen Shot 2022-08-31 at 10 08 32 PM" src="https://user-images.githubusercontent.com/107590196/187817500-eac4eea4-db50-4020-bc1f-9ee81232d438.png">

<img width="1407" alt="Screen Shot 2022-08-31 at 10 09 54 PM" src="https://user-images.githubusercontent.com/107590196/187817507-6ad30be3-20d5-4728-986f-605bb30ea30c.png">

