# Return-Yum: Food Wasting Project

## Overview

This mini-project was made during Ironhack's Data Analytics Bootcamp with the goal of using Web Scraping and API's techniques learned during classes.
The final objective of this project is for the user to save money and avoid food wasting. To do do, the user inputs the leftovers he has on the fridge - ingredients - and the tool web scrapes Continente Supermarket webpage - www.continente.pt - to gather the value of his leftovers (as Continente brand product) to calculate the price - so, the savings - the user is making by not throwing it in the garbage. Also, an API was used - https://spoonacular.com/food-api - to, given the same input - return possible recipes with the ingredients input. 

**Project Status:** may have improvements in the future.

---

## Technical Requirements

* **Web Scraping:** used the search bar of www.continente.pt to look for products filtered by brand - Continente;
* **API:** from https://spoonacular.com/food-api used 2 different APIs. One to retrieve recipe's name, recipe's ID and missing ingredients. The second, linked to the first, give you the recipe's instructions according to the recipe's ID;
* **Libraries imported:**
  * Pandas: building DataFrames
  * BeautifulSoup
  * Requests
  * ReGex: cleaning and uniforming numeric data
  * googletrans: translating inputs (targeted website built in Portugues, APIs built in English)
* Data and DataFrames cleaning and manipulation techniques

---

## Resources

* [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
* [spoonacular Recipe and Food API](https://spoonacular.com/food-api)
* [re - Regular Expression Operations](https://docs.python.org/3/library/re.html)

---

## Presentation

* Duration: 5 minutes;
* Food Wasting context;
* Technical process and challenges;
* Document in Microsoft PowerPoint.
