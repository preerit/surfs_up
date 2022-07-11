# surfs_up

## Overview of the analysis: Explain the purpose of this analysis.
Surf n' Shake shop is a store in Oahu, Hawaii (still in ideation phase) that sells surfboards and ice cream to locals, tourists. An ivestor, W. Avy, is ready to invest in this venture but wants to see some weather analysis before he backs up this idea. 
In this challenge, we are answering the investor's question about temperature trends. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
The tools we are using to do this analysis are SQLite and Python.

----

## Results: Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.
![June_tobs](/relative/path/to/img.jpg?raw=true "Optional Title")
![December_tobs](/relative/path/to/img.jpg?raw=true "Optional Title")
* The average temperature in June and December is in the range of 70-75, which is warm enough to support sales of surfboards and ice cream. Warm temperature continues to be one of the reasons why Hawaii attracts tourists year round!
* Standard deviation is in the range of 2.5 to 3.5. This indicates that there is no wide range of temperatures (minimum vagaries) within the same month
* Quartile analysis indicates that in the month of June, around 50% of temperature recordings is the range of 77 and in the month of December, it is in the range of 71. 

All the above are good reasons to believe that there are no sharp seasonal fluctuations in Oahu weather which makes it ideal for opening a Surf n' Shake shop.

----

## Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.
### High level summary of the results
* Max temperature in June is 83 while in December it is 78
* Mean temperature in June is 77 while in December it is 71
* Min temperature in June is 71 while in December it is 60
* The standard deviation is in the range of 2.5 to 3.5
* Outlier analysis for June indicates a 75 to 79 range and that in December indicates a 69 to 74 range
All the above indicate that there is no sharp weather fluctuations in Oahu and that there is a fairly predicatable warm weather year round that should keep surfboard and ice cream sales up at Surf n' Shake

### 2 Additional queries
* Query can be run to retrieve June and December data for multiple years to see year on year trend
* Query to check precipitation/humidity levels too see monsoon pattern for June and December 
