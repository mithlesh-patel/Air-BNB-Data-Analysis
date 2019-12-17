# Air-BNB-Data-Analysis
Analysing public data from AirBnB Boston and Seattle using python

1. Motivation of the project:

Using publicly available Airbnb's datasets,

- Try to analyse the price distribution of various properties listed on Airbnb in Boston and Seattle.

- Identifying the price range for each property type available on Airbnb in these cities.

- There are various room types available in each property, try to find which type is more expensive and vice-versa.

- Idenfying top-10 costliest zipcodes in these cities.

- Find correlation of selected featured with price.

2. Datasets available at below locations,

https://www.kaggle.com/airbnb/seattle/data

https://www.kaggle.com/airbnb/boston

files per city as follows

- listings.csv | detailed information about each listing in the city

- calendar.csv | date associated with each listing anf price during that time

- reviews.csv | review information about each listing in the city

3. Below python libraries have been used to perform analysis

- pandas to read and transform data.

- numpy to maintain data in numpy arrays

- matplotlib  and seaborn for data visualisation

- %matplotlib inline to render visalisation in ipython notebook itself.

4. Summary of the results

After analysing various attributes available in above datasets, I found below,

- A large number of listings are available between ~$50 to ~$150 in Seattle whereas the same is available between ~$75 to ~$250 in Boston which shows that Boston is little costlier than Seattle at least in terms of accommodations.

- Guesthouses, boat, villa seems most expensive in Boston and the average price is above $200. On the other hand in Seattle, condominium, loft, boat seems most expensive property type but the average price is less than that of Boston. There are some very cheap accommodations such as dorm available in both the cities with average price of ~$50 and ~$40 in Boston and Seattle respectively.

- Entire home or apartment is most expensive whereas shared rooms are more economic in both of the cities.

- Accommodates, number of bedrooms and the number of beds are positively correlated with price which means a positive change in these features will impact price positively.

5. Have a look to my blog on medium for more information,

https://medium.com/@mithleshpatel/read-this-before-packing-bags-to-boston-or-seattle-bc5db4055911

6. Acknowledgement

Above datasources are part of Airbnb Inside and downloaded from below locations,

https://www.kaggle.com/airbnb/seattle/data

https://www.kaggle.com/airbnb/boston
