# Weather-Analysis-with-SQLalchemy-in-Jupyter-Lab

## Purpose
Weather analysis of two sample months (June & December) to determine viability of a icecream surf store in Hawaii year round. Analysis was done using a SQLite Database and SQLAlchemy in Jupyter labs.

## Results
At first glance the two sample months June and December look quite similar, which is to be expected with Hawaii being close to the equator.

![This is an image](/Resources/June.png)

![This is an image](/Resources/dec_temps.png)

But there are some differences:
The maximum temperatures are very similar between June and December months. 
Both show a normal distribution with means and median (50% value) about identical respectively.
But the month of December shows a larger standard deviation and is shifted more to the milder temps as seen by the min temp.

## Summary
The differences between the summer and winter months with the June and December sample months show very little difference in average temperature. Based off temperature alone, since there is only a small difference between avg temps, I think this store would be viable business. I would further query the days of the month that saw precipitation (rain) in each and the avg. temp of those “rainy" days. These might show a larger difference the summer and winter months.
