# Projct3ToTurnInFinal
February 13, 2020

Dan, Cooper, Angel, Noah
StockX sneaker sales vs. US disposable income
Proposal:
For Immediate Release:
After a thorough vetting process, StockX has selected four up and coming data scientists to lead a data study that will reveal trends in sneaker purchases and disposable income. The study will provide valuable insights in shoe-nomics allowing business development to further strengthen StockX’s position in the sneaker resale market. 
It may be easy to cop a pair of yeezy’s, but wrangling data is not for the measly! 

Data Sources (two csvs) → Database (slurps two csvs into PG Admin) → query (flask and SQLalchemy) →  html and javascript (d3, plotly, mapbox.com, bootstrap, leaflet)

We have two csvs we’ll load into a cleaned, singular PGAdmin database.
Using ORM (SQLAlchemy and flask) we’ll connect the finalized data to our website, again using Flask.  The user will select which data they want on a dropdown of different states, and the website will query the data and make a table, a graph, and represent the data on a map as indicated below:

Our Three (+) stories are :
 Map of US that zooms into particular state with a marker showing the aggregate state data including the dollar amount per capita of disposable income, the per capita spending on sneakers, the two above figures as a percentage, and the most popular sneaker sold in that state
bar (possibly other types) graphs of sneaker shopping vs disposable income
summary table to show economic rank in the U.S. and other data AND top ten shoes sold (by state) table (possibly other data added here)
Top sellers of shoes graph by state

