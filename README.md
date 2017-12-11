
# Introduction
This research study is towards fulfillment of the final project requirement for the DATA 512 class of Fall 2017 at the University of Washington. This ReadMe document contains information on the project including details on the research questions, the datasets I have used, the provenance information for these datasets, copyright and licensing information for the code, data and documentation, and also some of the Human Centered Design aspects considered in this study.    

The goal of this work is to study and explore whether or not there is any dip in the number of people in Seattle who commute to work by bike during the colder days in winter as compared to days on which the weather is warmer. The scope of this study is limited to the commuters west of the lake washington as well as the Burke Gilman Trail north of 70th st. 

## Research Overview

To explore whether the colder temperatures affect the number of people commuting by bike in the City of Seattle, we need to know how many people commute by bike in Seattle and also what the temperatures are at that place during the times the bike count measurements are taken. Fortunately, the Seattle Department of Transporation has both of these information for various locations throughout the city and have made these datasets publicly available. The details of these datasets will be presented in the Dataset overview section below. For now, I would like to introduce two location points in the City of Seattle where I wish to explore the bike commuter counts as temperatures change across days of the year. The first reference point is towards the south end of the City of Seattle and is called Mountain to Sound Trail West of I90. This is the point where the I90 touches the city of Seattle. The second reference point is towards the north end of the city of Seattle and is called the Burke Gilman Trail North of 70th ST. 

These reference points on the two trails do not have weather stations on site. Rather, I have been able to find one weather station closest to each spot that can be used for an approximate temperature in these trails since the distance between the bike counter on the trail and the temperature sensor is not far away. Please see annotated maps below for more information. In each of the maps, the trail is indicated by the blue pointer and the weather station is indicated by the blue circle:

Annotated map for Bike Counter and Nearest temperature sensor for the MTS Trail West of I90:

![alt text](https://github.com/sumanbhagavathula/data512-finalprojectreport/blob/master/src/mtstrailwestofi90andclosesttemperaturesensor.JPG)

Annotated map for Bike Counter and Nearest temperature sensor for the Burke Gilman Trail North of 70th ST:

![alt text](https://github.com/sumanbhagavathula/data512-finalprojectreport/blob/master/src/burkegilmantrailandclosesttemperaturesensor.JPG)

## Research Questions and Hypothesis

With the above background, below were my research questions followed by the hypothesis:

* RQ1: Taking a reference point Mountain to Sound Trail West of I90, which is close to where I90 touches the city of Seattle, do the number of bike commuters at this point reduce in number on the colder days of winter compared to the warmer days during the rest of the year?

* RQ2: Considering another reference point Burke Gilman Trail North of 70th ST, is the trend similar to what is observed at the first reference point Mount to Sound Trail West of I90?

For the first research question RQ1, I had the following hypothesis:

* H1: On any given day, there are at least some people who commute to work by bike in Seattle.
* H2: There are at least some days in winter in Seattle that are very cold.
* H3: During the days on which the temperatures are colder, the number of people who commute by bike in the Mountain to Sound Trail West of I90 goes down.

For the second research question RQ2, below are my hypothesis:

* H1: The temperature fluctutations between the colder winter days and the regular warmer days rest of the year would be similar between the two locations, MTS Trail West of I90 and Burke Gilman Trail north of 70th ST.
* H2: The number of people who commute by bike in the Burke Gilman Trail north of 70th St reduces during the colder winter days as compared to the number on other warmer days of the year, similar to the pattern on the MTS Trail west of I90. 

Extending the hypothesis, I think it would be a safe generalization to say that the rest of the trails in the city of Seattle will see similar bike commuter count changes when temperatures go down in winter unless there were any drastic differences between these trails and other trails in the City.


<b>Why is this study important:</b>

1. When people do not commute by bike and take an alternative mode, this behavior leads to more congestion (either directly or indirectly, as elaborated below). More congestion can cause longer commute times and may also contribute to air pollution.   

    a. The congestion impact is direct when this alternative mode of commute is car or taxi because it directly adds a motorized vehicle on the road. The side assumption here is that the taxi taken by a person is otherwise free and not on road during that time. Also, the contribution to pollution is only when this motorized vehicle produces exhaust (eg. non-electric vehicles). 
    
    b. The impact is indirect when the alternative mode of commute is a carpool or a bus or a train, because even in this scenario there is an increase in the number of commuting people on the road by means other than bike and are still consuming the transportation resources. In this scenario it can be argued that there is no added impact when these people only increase the occupancy ratio of the existing fleet. And it is only when the fleets exceed their capacity requiring more fleet to be added that the real impact will begin to be noticed. 
    
2. As we know, bike riding is a very good form of exercise. We could conclude that when people bike to work they are getting better exercise. If these people do not bike to work and assuming some of them do not compensate this exercise with any other form, they are losing out on the health benefit.

    In both the scenarios mentioned above, we can see there is impact to humans and is an example of one of the values of a Human Centered Study Design.  
    
# Datasets

For this work, I take advantage of the following publicly available datasets: 

1. The bike traffic at different points in the city (including Daily, Weekly, and Annual patterns) in the Mountain to Sound trail are available at the City of Seattle Open Data portal's page on [MTS-Trail-west-of-I-90-Bridge](https://data.seattle.gov/Transportation/MTS-Trail-west-of-I-90-Bridge/u38e-ybnc). 

2. The bike traffic at different points in the city (including Daily, Weekly, and Annual patterns) in the Burke Gilman trail are available at the City of Seattle Open Data portal's page on [Burke Gilman Trail North of 70th st](https://data.seattle.gov/Transportation/Burke-Gilman-Trail-north-of-NE-70th-St-Bike-and-Pe/2z5v-ecg8). 

3. The road and air temperature data for different locations throughout the city is available at the City of Seattle Open Data Portal's page on: [Road Weather Information Stations](https://data.seattle.gov/Transportation/Road-Weather-Information-Stations/egc4-d24i)



# Copyright and Licensing

The code, text of the repository will be governed by the MIT License to be included in the [LICENSE file](https://github.com/sumanbhagavathula/data-512-finalproject/blob/master/LICENSE)

The datasets from City of Seattle's Open Data Initiative website (and may be included in this repository) as well as any future derivative work and data in this project repository is available under the [Creative Commons 0](https://creativecommons.org/publicdomain/zero/1.0/). 

More information on this can be viewed at the City of Seattle's Open Data Initiative [Information page](http://www.seattle.gov/tech/initiatives/open-data), the [Warranty information page](https://data.seattle.gov/stories/s/Data-Policy/6ukr-wvup/), the [policy page](http://www.seattle.gov/Documents/Departments/SeattleGovPortals/CityServices/OpenDataPolicyV1.pdf) and the [privacy page](http://www.seattle.gov/tech/initiatives/privacy)

<b>In addition, the City of Seattle requires the following disclaimer be pasted into any derivative works that use their datasets (see:  [City of Seattle's Open Data Initiative Policy page, "Source Data" section](https://data.seattle.gov/stories/s/Data-Policy/6ukr-wvup/) )</b>

The data made available here has been modified for use from its original source, which is the City of Seattle. Neither the City of Seattle nor the Office of the Chief Technology Officer (OCTO) makes any claims as to the completeness, timeliness, accuracy or content of any data contained in this application; makes any representation of any kind, including, but not limited to, warranty of the accuracy or fitness for a particular use; nor are any such warranties to be implied or inferred with respect to the information or data furnished herein. The data is subject to change as modifications and updates are complete. It is understood that the information contained in the web feed is being used at one's own risk.



## Description of the process
The end to end process of this analysis work will broken down into four steps:

1. Data Acquisition
2. Data Processing
3. Analysis and Visualization
4. Conclusion

## File structure
The source code, data (raw and processed) are placed in the following structure:

### Source
The source code is located in the [github repo source code file](https://github.com/sumanbhagavathula/data512-finalprojectreport/blob/master/src/hcds-finalproject.ipynb) and containing documentation and code for all the three steps mentioned above.

### Data
1. [Raw Data](https://github.com/sumanbhagavathula/data512-finalprojectreport/tree/master/src/) will contain any raw data files. 

2. [Processed Data](https://github.com/sumanbhagavathula/data512-finalprojectreport/tree/master/src/) will be the location for the processed data

3. [Analysis and Visualization Data](https://github.com/sumanbhagavathula/data512-finalprojectreport/tree/master/src/) will contain any data transformations that were generated in the analysis phase and copies of any visualizations that may be created as part of this work.


# Dependencies

The City of Seattle mentions on their [Data Policy page ("see Right to Discontinue Feeds") section](https://data.seattle.gov/stories/s/Data-Policy/6ukr-wvup/) that they do reserve the right to discontinue or provide any or all of the data feeds at any time. This implies that anyone trying to reproduce my project's research work could be impacted if the any or all of the datasets mentioned in this Repository are taken down.  


# Acknowledgements

I would like to thank the instructor and TA for the class (Prof. Jonathan Morgan and Oliver Keyes respectively) who have gathered information on the datasets and allowed us to use them for my work. Also, many thanks to the City of Seattle's Leadership and the Open Data Initiative team for providing the valueable datasets that were of use in this research study, without which this research work may not have been possible. 
