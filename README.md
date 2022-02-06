# -PyBer_Analysis_Challenge
Analysis of ride-sharing data for visualization purposes.

# Overview of the Analysis
The management team of this ride-sharing company has requested that Python and Pandas can be used to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, a multiple-line graph can be created that shows the total weekly fares for each city type. This visualization will be important for understanding and illustrating the data in a way that can tell a story. The story in this case being the time span for which weekly fares is tracked for the city type.

# Results: 

The dataframe was created by combining the city data and multi-line rider data. From this new dataframe, various conditions were extracted including the total number of riders, drivers, mean fare per rider and driver. These pieces of information were used to create the summary dataframe shown below. 

![Summary PyBer Date Frame](Resources\pyber_analysis_summary_df.PNG)

*Figure 1: PyBer Summary DataFrame*

It's indicative in this summary table that the urban area has significantly more rides than the rural or suburban areas. However, the ratio of riders to drivers is much higher in the rural areas than in the urban areas. This means that the driver is making a lot more rides than if they stayed in the urban area. Given the significant amount of rides in the urban area, it would also make sense that it has the highest amount of total fares.

With respect to the fares, the urban areas have shown to have a lesser fare per rider as well as a lesser fare per driver. This is a logical finding given the magnitude of the total values associated with the urban area. As expected, it is much more expensive to drive or ride in the rural area.

In order to visualize the rides on the basis of time, the following chart was created to illustrate the price of fares over time.

![Fare Summary PyBer](analysis\PyBer_fare_summary.png)

*Figure 2: PyBer Fare Summary*

Within this line graph, it is apparent fares tend to spike in between February and March. Each line shows a different state by which they have increased fares. For example, the Janary month shows an uptick for suburban areas yet an increase for urban and stagnation for rural. At the end of April, urban and rural areas show a decrease in ridership fares and suburban sees an uptick. 

# Summary: 

Based on the results, there are three business recommendations to the CEO for addressing any disparities among the city types.

1. Empower drivers by increasing the fare amount so that they can be somewhat equal with the other tyoes.
2. Encourage more riders to take ride-sharing as a means 
3. Promote ride-sharing on weeks where there has historically shown decrease traffic volumne.

In taking these items, and incorporating them into the company's bottom line will most likely reap future benefits.