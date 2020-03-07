<h1>Battle of the Neighborhoods!</h1>
<h2>Topic: Determining the best location for a Business start-up in the city of Calgary, AB Canada</h2> 
<h3>Author: Karim Khan</h3>
<h3>March 2020</h3> 

<h2>Introduction/Business Problem</h2>
Starting a new business is a big decision to make as it requires in-depth planning and execution. This project attempts to map out, segment and explore the neighborhoods in the city of Calgary, AB Canada. The goal will be to help entrepreneurs and prospective business owners in this city decide optimum locations to start a new business. Several factors will govern location selection such as the type of business, target customer base, proximity to public transit and size of physical store, to name a few.

<h2>Data Used</h2>
A number of datasets and tools will be exploited to tackle the subject. To start off, a comprehensive <a href=https://en.wikipedia.org/wiki/List_of_neighbourhoods_in_Calgary#List>list</a> showing the breakdown of the neighborhoods, their physical size and population across Calgary will be scraped and structured into a Pandas Data Frame. Next, geospatial information (latitude and longitude) will be extracted using geocoder package in Python for each neighborhood. Foursquare location data will be the main API server leveraged to explore the different venues and types of businesses that currently exist in those neighborhoods. A number of data science skills will be utilized in this project, such as data wrangling, exploratory data analysis and use of Machine Learning, namely K-Means Clustering algorithm to cluster and analyze the neighborhoods and help in selecting the best location for a business start-up.  