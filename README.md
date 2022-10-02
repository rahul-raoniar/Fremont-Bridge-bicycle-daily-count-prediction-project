# Seattle Fremont bridge bicycle daily count forecast project

The Fremont Bridge Bicycle Count dataset includes bycycle count from October 2012 to 2019. It consist of count records (number of bikes that cross the bridge using the pedestrian/bicycle pathways). 
Inductive loops on the east and west pathways count the passing of bicycles regardless of travel direction.

### Forecasting the bicycle counts

* This notebook consist of forecasting codes
* Forecasting is done using Meta's prophet library. 
* Here I have forecasted the Bicycle counts for next 2 years.
* Included holidays (Washinton) to observe the impact on daily counts.
* Performed a forward-chaining cross-validation.

![Alt text](forecastplot.png)