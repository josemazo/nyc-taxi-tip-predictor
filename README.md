nyc-taxi-tip-predictor
======================

First of all, I must say thank you to [Chris Whong](https://twitter.com/chris_whong) for obtaining the incredible dataset that it's used in this project. [Here](http://chriswhong.com/open-data/foil_nyc_taxi/) is his little odyssey to get the data.

![Map](./resources/map_1.png "Map")


TL;DR
-----

After cleaning and getting a sample from the original dataset, it's possible to predict, with an `accuracy of 71.74%`, if the tip of a trip in a NYC taxi it's going to be `less thant 20%` or `greater than or equal to 20%` of the charge, without the possibility to use information about the passengers, a *essential* data for trying to accomplish this task.


Extended version
----------------

For read an extended version there are some IPython `notebooks` that describe the complete process. You can find them in this repo, but for a better reading use [this](http://nbviewer.ipython.org/github/josemazo/nyc-taxi-tip-predictor/tree/master/notebooks/) `nbviewer` link.
