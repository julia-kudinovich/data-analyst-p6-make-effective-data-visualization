Data Analyst Nanodegree Project 6: Make Effective Data Visualization

# Summary

This visualization shows survivals distribution between 3 different passenger classes. It is built based on the Titanic dataset which contains demographics and passenger information from a subset of the 2224 passengers and crew on board the Titanic.

Plot show that the better the class the higher is the percentage of survivals in that class.  First class passengers had 67% survival rate while 3rd class passengers only had 22% survival rate.


# Design


In my design, I decided to use vertical 100% bar plot to show correlation between survival and passenger class. This type of graph is chosen because it represents a proportion of survived/died passengers in total passenger count very well.

Bars on the plot are colored green/red which corresponds to proration of survival/not survival of the passengers in the specific class. The choice of colors is explained by the common usage of green/red colors when direct opposites needed to be displayed.

x axis corresponds to the class of the passenger (1, 2, 3) and y axis corresponds to the percentage of survived/not survived passengers since I am using the vertical 100% bar plot. Should I choose horizontal 100% bar plot axes would have been switched.




# Feedback

### Person 1
* From the graph it is clearly seen that there is a relationship between survival and passenger class.
* One thing that is not clear straight away is what 0 or 1 on the legend mean. Even though it gets clear after the inspection of the graph the legend needs to be changed to something more concrete. Same goes for the tooltip.


### Person 2
* The main takeaway form the graph is that percent of people died in each class increases from 1st to 2nd to 3rd class. Percent of people survived in each class decreases from 1st to 2nd to 3rd class.
* It is hard to read axes titles and legend: they are too small.
* Tooltip is confusing. What does PassengerId percent mean?

### Person 3
* The context is not clear straight away. I had to think for some time
* Legend and tooltip do not help much in making the graph clear. I would even say tat they make it harder to understand the graph instead of helping. PassengerId plus some percent value is the most confusing value in the tooltip.


In my final version, I have fixed these formatting and data representation issues.


# Resources

[Dimple.js documentation](https://github.com/PMSI-AlignAlytics/dimple/wiki)

