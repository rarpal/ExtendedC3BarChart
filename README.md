## [Extended C3 Bar Chart](http://rarpal.github.io/ExtendedC3BarChart/)

### What I have extended
I have made use of the extendability features of c3js to customize the way the bars on the chart are highlighted.
Here I have redefined the selectPath method to increase the highlight brightness from the default 0.75 to 1.75.
I have some logic when I dont want certain bers to be highlighted. For those I set the brightness to 0.

### Further development
* I also want to either change the fill pattern or draw borders around the selected bars
* I think what would be better is to have the brightness level to be included in the config object, rather than hard-coded here
