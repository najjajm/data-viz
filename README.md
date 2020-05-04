# data-viz
An assortment of data visualization projects.

## Hailstorms USA
For this visualization I wanted to investiagte if severe weather (specifically, hailstorms) were becoming more common, more widespread, and more severe in the USA. I scraped the National Oceanic and Atmospheric Administration (NOAA) for data on severe weather dating back to 1950 (hailstorms were first reported in 1955). I removed entries from the current year as the data are still in flux.

The figure consists of three panels. In the top plot, I made a bar chart of the total hailstorms in each year (summed across all states and counties). This clearly shows a substantial increase in hailstorms since 1955, albeit with what seems to be a decreasing trend since ~2005. Next, I wondered if hailstorms were becoming more widespread (i.e. if storms were simply increasing in a handleful of states or if more states have been experiencing hailstorms in recent years that haven't previously). The middle plot shows a heatmap of total hailstorms in each state (summed across all counties) over the years. Though there are a few states (e.g. Texas, Kansas, and Oklahoma) that are clear hot (or, cold) spots, the chart does seem to show that more states have been experiencing hailstorms since ~1995. Finally, I wondered if hailstorms were becoming more severe. To address this I made a stacked bar chart (bottom panel) showing the distribution of hail diameters (across all storms from each year). This actually shows something surprising: the steady increase in total hailstorms from 1955 - 2005 actually coincided with a decrease in the proportion of severe hailstorms. That is, between 1980 and 2005, most storms increasingly consisted of small sized (0-1") hail. However, the apparent decrease in total storms in the past ~15 years seems to coincide with a moderate increase in hail size as 1-2" hails are becoming more common.
