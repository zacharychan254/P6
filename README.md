Introduction:
I created this interactive bar chart for my reader to know the players height distribution. And I wanna show the relationship between players height and their HR, so I created scatter plot.

Design:
Since the players can be classified as 3 group, they are Right hand, Left hand, and both hands.
So the interactive part is about a dropdown list for reader to choose the group they are interested in.
For the bar chart, I would like to know the distribution of players height, because I m not a baseball fans, so I wonder that if height is as important as in NBA. 
For the scatter plot, since the database do not contain any data of players position, but it contained Home Run Data, so I want to discover that any correlation between Home Run and Players' height.
And I also want my reader can discover it by themselves. 

Feedback:
The most challenging part is update the chart, because we have to select the right element and delete the old connected data. Afterward, we can build the new chart with new data again. Since the data connecting part is really confused, so I spent lots of time to study it. 

Classmate A suggested me that setting an event when I move the mouse on the bar chart, the chart will show the specific data.

Classmate B suggeted me that using different color to indicate the handedness of player is better than use different shape with same color, becasue he thinks that in my chart, color is more eye catching than shape.

Udacity tutor suggested me that use Math.random() function to jitter the dot in scatter plot, since the x axis data is integer format, so the dot will be overlapped to each other. 

References:
http://bl.ocks.org/KatiRG/5f168b5c884b1f9c36a5
http://www.d3noob.org/2013/07/arranging-more-than-one-d3js-graph-on.html
http://bl.ocks.org/jonahwilliams/2f16643b999ada7b1909
https://bl.ocks.org/floofydugong/9c94ab01d8c3ed8ea3821d4a7e119b07
