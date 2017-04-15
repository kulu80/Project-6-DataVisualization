# Data Visualization-Titanic Dataset

## Summary
Three barcharts were used to show the total number of people who survided as per thier class, sex and average age of people survived for each class and sex. 

## Design
The Titanic dataset were downloaded from the link given in the file project. Titanic dataset which contains information for 891 people of the 2224 passangers on board of the Titanic that sank in North Atlantic Ocean in the early morning of 15 April, 1912, after colliding with an iceberg during her maiden voyage from Southampton to New York City.The dataset contains many missing values, before data viaualization was made some EDA was employed in python. Forexample only the ages of 714 people from 891 passanger,as age is a numerical value, the missing values was filled with the mean of the population. The visualization was designed to show  survival of passsager as per thier class, sex and also averge age survied for each class and sex. As the dataset contains many categorical varaibles such as sex and class, bar char is a suitable means to visualized the dataset and I choose dimple.js for data visualization due to its simplecity of plotting charts.

We can see from the above plot that most of the passanger (about 550) were perished during the crash only about less than 350 were survived. Now, let further our analysis by adding other factor to our analysis in this case sex and class of passangers. The bar graph below tells us that on many of the survivor were females and most of these passanger were in the first and secodn class. In the males case also the number of surviors in the first class were higher than the other classess. We may speculate that class of the passangers contributed on the survival rate of both female and male passanger., however in all class the number of female passanger surval was by far larger than that of male passanger, that might be due to the fact that priority for rescue could be given to female passangers

## Feedback

### Feedback 1
Your chart was a bit messy & no clear headlines & legend. If there is some explanation like a bold headline then these charts would make sense. The insights is not so much of a surprise and if you just create a small tweak in the legend, x-axis & y-axis then this would looks good. The data clearly favors your initial hypothesis, women children & elders are prioritized to board the baot first.
### Feedback 2

The chart is interactive, that's nice. But why the second chart is revert and not in-line with the other chart. Switch x-axis & y-axis with each other and I think the chart will looks much better. By the way, the first chart to split between classes is cool but I think you can make it even better by combining gender & classes to see if there's different behavior in different classes. Broadly speaking, the chart looks intuitive & only needs a few small tweak.
### Feedback 3

The second chart looks a bit weird and too much junk information, there's no need to include different age in different age bracket like that. There's not much information to show. And for the first chart, split the column into two, a stacked-bar wouldn't be necessary. Also, you also needs to clean up the headline & make clear of the axis, what is PClass? Can you makes it a bit clearer. Overall, this chart is straightforward.

