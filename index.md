## Crime Statistics in San Francisco in Summer 2014

In San Francisco, during the peak crime time of 5 pm - midnight, the North-Eastern districts have a higher incidence of Larceny/theft, Assault, Drug/Narcotics, while Vehicle theft is more in the Southern districts
## Incident frequency
![](https://sangsomwork.github.io/Crimestats_SF/Incidentfrquency.png)
This plot shows the frequency of occurence of each category of crime incidents. Larceny/theft is the most frequently occuring category(9,466 incidents or 32% of the incidents). While "Other offenses" and "Non-criminal" categories were next in order of requenct, for the rest of the analysis, I chose to include the more specific categories of "Assault", "Drug/Narcotic", and "Vehicle Theft"

## Crime incidents as a function of time
![](https://sangsomwork.github.io/Crimestats_SF/Timeseries.png)
This plot shows the number of incidents occuring in each category as a function of hour of the day (0 indicates 12 AM and 23 indicates 11 PM). Here we see that the number of incidents has a sinusoid-like behavior as a function of time. Larceny, Narcotic, and Assault incidents related incidents reach a high value between 5 -10pm, and reach a low between 2- 5 am. The dashed lines are trendlines that I fit to the curves using Polynomial fitting of order 4. This helps to highlight a smooth trend over the noisy curves.

## Crime as a function of geographic location during peak hours
![](https://sangsomwork.github.io/Crimestats_SF/Map.png)
I chose a time window between 6 pm to midnight to visualize the crime incidents in each category within each region. The circles shown in the plot are centered at the average latitude/longitude in each Pdistrict and the size of the circle is proportional to the number of incidents in that region. The sizes are expressed as a percent of the total in each category so that large differences in magnitude in one category do not dwarf the differences in other categories. For example, Larceny incidents are higher than other categories, so visualizing abolute numbers would just show small circles for other categories making it difficult to judge relative occurences of crime.

The plot shows that for Larceny, Assault, and Drug related incidents, the North-Eastern regions have larger incidence of crime. Southern district has the highest incidence of Larceny/Theft, Drug/narcotic, and Assault. For Vehicle theft, however, the districts in the South of San Francisco have a higher number of crimes. Ingleside has the most frequent incidence of vehicle theft.

## Interactive dashboard
I have created an interactive Tableau dashboard to browse through the plots shown above. Selecting a category on the right enables you to highlight the relevant parts of each of the other plots. Please click the link below to view the dashboard.

[Interactive dashboard](https://public.tableau.com/views/Crimestats_SF/Dashboard1?:embed=y&:display_count=yes&publish=yes)

