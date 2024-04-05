# python_api_challenge
Module 6 Assignment
For this assignment I used openweathermap to generate an API key for my WeatherPy document and Geoapify for my geoapify_key for my CityPy document.

In WeatherPY: Information was taken on March 5th, 2024. We have a set of 618 cities, four figures (fig1, fig2, fig3, fig4) and a computation of linear regression for each of the four figures, sepearated by the northern and southern hemispheres. For this code, I used linregress to find slope, intercept, rvalue, pvalue, stderr, plt to plot our scatter plots and regression lines, a for loop to fetch the information for each city, and dataframes to create a dataframe. Additionally, I used .dtypes to check for the dtype of dates and converted it by using .astype({"Date": "datetime64[s]"}). To change the dtype I used this website: https://numpy.org/doc/stable/reference/arrays.datetime.html 

In CityPy