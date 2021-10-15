# Bikesharing

## Overview of the Analysis 
### Purpose of this Analysis 

The purpose of this analysis is to present a business proposal for a bike sharing company in Des Moines based off of bike sharing data from Citibike in New York. 

The analysis consisted of three parts:
1. Downloading a dataset from the Citi Bike System Data page from August 2019 (201908-citibike-tripdata.csv.zip). A dataframe was created and the "tripduration" column was converted from an integer to a datetime datatype. Afterwards, the updated dataframe was exported to a CSV file.
2. The updated CSV file was imported to Tableau and five visualizations were created that show how long bikes are checked out for all riders and genders, how many trips are taken by the hour for each day of the week for all riders and genders, and a breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender. Several other visualizations were created earlier in the module, and three were chosen to be included in the results to provide better insight.
3. A story was created using Tableau to illustrate key outcomes of the NYC Citibike data. 

Link to the story on Tableau can be found here: https://public.tableau.com/app/profile/ewa.a.szyszkowska/viz/Bikesharingstory/BikeSharing

## Results
### Visualizations with description of results for each

#### Visualizaton 1
The first visualization is a text displaying the total number of bike rides that occurred in August of 2019.  
![image](https://user-images.githubusercontent.com/84869167/137415148-7ff9468a-48d5-4ccd-afb2-5aaf9f76ea2f.png)

#### Visualizaton 2
The second visualization is a horizontal bar graph that illustrates the peak hours of bike usage. The highest rates of usage occur during morning and afternoon rush hours, between 7:00 am and 9:00 am and between 4:00 pm and 7:00 pm. 
![image](https://user-images.githubusercontent.com/84869167/137415280-8accd1f2-ab3d-4e2b-826c-a0d2bdedd9a4.png)

#### Visualizaton 3
This pie chart displays the proportion of short-term customers to annual subscribers of the bike sharing service.
Of the 2,344,224 total bike rides, 443,865 (18.9%) were carried out by short-term customers, while 1,900,359 (81.1%) were carried out by annual subscribers.  
![image](https://user-images.githubusercontent.com/84869167/137416552-404e7cf0-8255-4da9-98ef-fb37da3863ae.png)

#### Visualizaton 4
This pie chart shows the gender breakdown of Citi Bike riders. 
1,530,272 or 65.3% of users are male
588,431 or 25.1% of users are female
225,521 or 9.6% of users are of unknown gender
The legend for th visualization is labeled "Gender Converted" because the datatype in the "gender" column of the imported CSV file was converted from number values to string values. 

![image](https://user-images.githubusercontent.com/84869167/137417209-ff87088c-d0ae-4bab-8abe-2d97e09392d2.png)

#### Visualizaton 5
This graph displays the length of time that bikes are checked out for all riders. Most bikes are checked out for an hour or less, with the most bikes being checked out for about 5 minutes at a time. 
![image](https://user-images.githubusercontent.com/84869167/137417398-419eaa54-b072-4a74-82b6-803a2ca08b77.png)

#### Visualizaton 6
This graph displays the length of time that bikes are checked out for each gender.
The most number of bikes are checked out by males with a duration time of about 5 minutes. 
Most females check bikes out for a duration of about 6 minutes. 
Most users of an unknown gender check bikes out for a duration between 6 and 25 minutes. 
![image](https://user-images.githubusercontent.com/84869167/137417930-5237fbda-3d67-43e2-9795-1036061dde2e.png)

#### Visualizaton 7
This heatmap illustrates the number of bike trips by weekday for each hour of the day.
This heatmap reflects the results of the bar graph that illustrated the peak hours of bike usage for the weekdays. 
More bikes are used during the morning and afternoon rush hours (8:00 am and 5-6:00 pm).
During the weekend, bike usage is gradually spread out throughout the morning, afternoon, and early evening hours. 
There is very little usage at night for both weekdays and weekends. 
![image](https://user-images.githubusercontent.com/84869167/137418923-844c3d2f-0102-4910-b13a-eb46063834a7.png)

#### Visualizaton 8
This heatmap illustrates the number of bike trips by gender for each hour of each day of the week.
Male and female usage strongly reflects the trend of high usage during the morning and afternoon rush hours (8:00 am and 5-6:00 pm). Customers of an unknown gender appear to make the most number of trips on the weekends. 
![image](https://user-images.githubusercontent.com/84869167/137419329-67c1dc3c-0f5c-41d4-8a0f-6ccdc39b7765.png)

#### Visualizaton 9
This heatmap illustrates the number of bike trips by gender and customer type for each hour for each day of the week.
The highest number of bike trips occur amongst male and female subscribers on Monday, Tuesday, Thursday and Friday.
On the other hand, the most number of bike trips among unknown genders occur on Sunday and Saturday. Most unknown genders are customers, not subscribers. 
![image](https://user-images.githubusercontent.com/84869167/137419476-994ec3cf-487d-4933-a066-50705de3db21.png)


## Summary
### Summary of the results plus suggestion of two additoinal visualization
In conclusion, most users of the Citi bikesharing service are male subscribers which use the bikes for about 5 minutes during the weekday morning and afternoon rush hours. 
Two additional visualizations that would provide more information to us would be a graph that illustrates the average distance the bikes are used for by gender, as well as the type of use by gender (for recreation, for getting to/from work, or for actual work like for delivering items). Another visualization that would be helpful is to measure the amount of users that live in that city vs tourists that are just visiting. 
