# NYC Bikesharing Analysis

## Overview
The purpose of this project was to utilize Tableau to create several visualizations from a New York City bikesharing dataset. Before importing the CSV file into Tableau, I changed the trip duration column datatype to "datetime" using the Pandas library in Python. This step was critical because it allowed me to narrow down trip duration to hours and minutes in my charts.

## Results
![image](https://user-images.githubusercontent.com/95651156/162646521-2ef412dc-d000-40a9-81b5-60a2c537e22a.png)

The above visualtization shows that the vast majority of NYC bikesharing trips range between 0-60 minutes, with 5 minutes being the most common trip length.

![image](https://user-images.githubusercontent.com/95651156/162646772-813637c6-6890-4460-ab18-b20d5f2a7e63.png)

There are a few conclusions to be drawn from the above visualization. One conclusion is that males are by far the most prevalent bike sharers in NYC compared to females and unknown users. Additionally, the visualization shows that males, females, and unknown users all follow a similar distribution when it comes to trip length for bikesharing. 

![image](https://user-images.githubusercontent.com/95651156/162647025-04220bcb-f845-401c-a66f-3946bc620e68.png)

The above visualization displays the number of trips within a given hour of the day for each day of the week. I see that 6-9 AM and 5-7 PM contain the highest volume of trips during the week, whereas 11AM-4PM is where the bulk of trips occur during the weekend. This makes sense because the bikesharing program is likely used by many people to commute to and from work during the week while also being a popular afternoon activitiy on the weekend.

![image](https://user-images.githubusercontent.com/95651156/162647377-98008a75-b2a5-4953-a9e3-9ad5e871f1a1.png)


The above visualization reinforces the previous notion that males are the most frequent participaters in the bikesharing program. Additionaly, I see that a vast majority of riders that share their gender are subscribers, whereas unknown users tend to be customers. Lastly, for both males and females, the day of the week with the most rides is Thursday. 

![image](https://user-images.githubusercontent.com/95651156/162648007-fce47ecf-dba8-4d26-b497-531569c7d9d5.png)

This final visualization reiterates several conclusions from earlier. In particular, I see again that bikes are used most frequently during commuting hours during the week as opposed to during the middle of the day on the weekend. It also shows once again that males, females, and unknown users rank 1-3 in most prevalent riders.

## Summary

### Main Takeaways

* A vast majority of NYC bikesharing trips range somewhere between 0-60 minutes, with five minutes being the most common length of trip (146,752 rides)
*  Males make up the majority of the NYC bikesharing rider base
*  From Mon-Fri bikesharing volume is highest during work commute hours
*  From Sat-Sun bikesharing volume is highest during the middle of the day
* Thursday has the highest bikesharing volume for both males and females
*  Males, females, and unknown users have similar distributions when it comes to trip duration and most common times to ride (both day of week and time of day)

## Possible Additional Visualizations

One additional visualization I would consider making with this dataset is a heatmap that has birthyear (most likely several ranges of birthyears) and day of week as the columns and time of day as the rows. This would allow me to see how trip volume for different age ranges differs for different hours for each day of the week. Additionally, I think it would be cool to create a map that shows the most common routes (the most common combinations of starting location and ending location). In doing this, I would attempt to color code the 5-10 most common routes by making the dots for the starting and ending location the same color.

