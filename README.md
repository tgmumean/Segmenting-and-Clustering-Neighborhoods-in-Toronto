# Segmenting-and-Clustering-Neighborhoods-in-Toronto

#### PART 1: 
Use pandas, or the BeautifulSoup package, or any other way you are comfortable with to transform the data in the table on the Wikipedia page into the above pandas dataframe. 

To create the above dataframe: 
- The dataframe will consist of three columns: PostalCode, Borough, and Neighborhood.
- Only process the cells that have an assigned borough. Ignore cells with a borough that is Not assigned. 
- More than one neighborhood can exist in one postal code area. For example, in the table on the Wikipedia page, you will notice that M5A is listed twice and has two neighborhoods: Harbourfront and Regent Park. These two rows will be combined into one row with the neighborhoods separated with a comma as shown in row 11 in the above table. 
- If a cell has a borough but a Not assigned neighborhood, then the neighborhood will be the same as the borough.
- Clean your Notebook and add Markdown cells to explain your work and any assumptions you are making. 
- In the last cell of your notebook, use the .shape method to print the number of rows of your dataframe. 

#### PART 2: 
Now built a dataframe of the postal code of each neighborhood along with the borough name and neighborhood name, in order to utilize the Foursquare location data, this part we need to get the latitude and the longitude coordinates of each neighborhood. Use the Geocoder package or the CSV file to create the dataframe. 

#### PART 3:
Explore and cluster the neighborhoods in Toronto. You can decide to work with only boroughs that contain the word Toronto and then replicate the same analysis we did to the New York City data. It is up to you. 

#### I have attached a picture In case of unable to open 
- Picture 1: visualize the map of Toronto with neighborhoods 
![Image description](https://github.com/tgmumean/Segmenting-and-Clustering-Neighborhoods-in-Toronto/blob/master/capture-20200418-170307.png)

- Picture 2: visualize the map of the resulting clusters
![Image description](https://github.com/tgmumean/Segmenting-and-Clustering-Neighborhoods-in-Toronto/blob/master/capture-20200418-170342.png)
