# 1. CitiBike Trip Analysis
    The purpose of this project is to carry out analysis using the CitiBike data for August month to understand trends and to use data 
    visualization tool Tableau to create a story of the analysis.
    [link to dashboard](https://public.tableau.com/app/profile/isabella.helliwell)
    
# 2. Resources
    - Tableau Public Application Software
    - Jupyter Notebook
    - Pandas DataFrame
    - Python
    - Files Citi Bike trip data: 201908-citibike-tripdata.csv.zip
    - Files created citibike_data.csv, NYC_CitiBike_Challenge.ipynb
    
# 3. Analysis
    The citibike trip histories for August month consists of the following information:
    - Trip Duration
    - Start Time and Date
    - Stop Time and Date
    - Start station Name
    - End Station name
    - Station ID/ Bike ID
    - Station Lat/Long
    - User Type
    - Gender/ Year of Birth
    
    For this analysis, Jupyter Notebook was used to create a dataframe for the 201908-citibike-tripdata.csv, and to convert the tripduration column to a
    datetime datatype.
    This dataframe was exported as a new csv file, without the index and saved as "citibike_data.csv". This data is used for the analysis.

# 4. Results
## 4.1 Gender 
    Gender is divided into 3 categories: 0=unknown, 1=Male, and 2= Female. Shown below is a graph representing the gender division vs bike trips. 
    The graph shows the first 3 hours of trip duration. It can be seen that the majority of trips last less than 1 hour, with a peak of around 4-8 minutes.
    We can also see that the majority of bike users are Males topping with 108087 trips compared to Females 34151, and unknown gender 7389 trips.
![image](https://user-images.githubusercontent.com/85843030/134773361-215f2c9c-f063-41d9-a0bb-fd6fb8bda0cc.png)



    Below, shown is the graph for trip start hours for the Gender category.If we look into what time of the day and weekday each gender prefered using bikes, 
    we can see that for both Females and Males, most trips happen Thursday starting at 6pm. With the males having the most bike trips 30749, followed by 
    Females 11336 trips. Saturday around 12pm seem to be the preferred start bike trip time for gender Unknown, with 5669 trips.
 ![image](https://user-images.githubusercontent.com/85843030/134774127-3237bf1b-6b39-4db1-8d50-28c749e29d69.png)
   
   
   Furthermore, if we look into the different gender proportions of user type, i.e customers ( 24 hour pass or 3-day pass users) and Subscriber (Annual Members),
   we can see from Graph below, that the majority of the bike trips occur once again for the Subscriber Male with 259316 trips.
![output3](https://user-images.githubusercontent.com/85843030/134774442-3f260d90-0e13-44db-b103-356744e53c70.png)
   
   
## 4.2 Trip Duration
    Looking at the Graph representing the Trips vs the Tripduration, we can see that the majority of the trips occur within one hour. 
 ![image](https://user-images.githubusercontent.com/85843030/134776599-1ac9a311-4680-4cc2-8408-d82865c793e8.png)


    Plotting a Box and whisker graph, we can see that the graph should be positiv skewed, i.e skewed to the right. We can also calculate this
    by using the Quartiles and Median values. (see graph)
    We can also see that the value that occurs most often is 5 min trips.
![image](https://user-images.githubusercontent.com/85843030/134780261-c837714d-4010-4f2e-aafe-b0e5b5372960.png)


## 4.3 Bike Trip
    Looking at the starting location for the bike hires below in Graph, we can see that the central areas are where most of the bike rentals happen.
![image](https://user-images.githubusercontent.com/85843030/134781640-2ddcd845-67df-4244-ac90-9e382a904482.png)


    Overview of the bike rentals vs hours is shown in Graph below:
![image](https://user-images.githubusercontent.com/85843030/134780740-26469122-980d-4bf5-b6aa-951a66b34b03.png)

  
    From the Graph, we can see that most bike rentals occur between the hours of 7-9am and 4-7pm, which coinsides with comuting to and from work.
![image](https://user-images.githubusercontent.com/85843030/134780671-8c3550f8-8ab6-4e39-8b0d-0cc78fbfd0ff.png)

    We can also see from Graph below that the most popular time for bike trip is Thursdays and 5-6pm.
 ![image](https://user-images.githubusercontent.com/85843030/134780855-a405b386-c19c-414e-a1d0-c1a93a13d55f.png)

# 5. Summary
    From the above graphs, we can conclude the following:
        * Majority of bike users are Male
        * The top bike users are subscribers
        * Preferred weekday to use a bike is Thursdays
        * Most trip durations are less than 60min
        * Most popular times to use a bike is between 7-9am and 4-7pm
        * The least used time for bikes is between 12-5am
        * There are more bike users in the more central areas of NY, than the suburbs
        * Peek time to use bike is 6pm for all gender categories
        

# 6. Additional Analysis
## 6.1 Bike Trip vs Age 
    Additional analysis have been carried out to see find a trend between age groups and trips taken. Firstly we look at the age data vs trips by birth year.
    Graph below shows that the majority of the bike users are born in 1969, which when the data was gathered (2019) would make these groups 50 years old.
    The next 2 age groups that use bikes are born 1989, and 1990, which would make them 29-30 years old. Looking further at the data, we can see that the 
    graph is skewed to the left, which indicates that the younger users are using the bikes more than the older generation, with exception of 16-20 year olds.
![image](https://user-images.githubusercontent.com/85843030/134781102-b28615ce-4694-4023-9826-266181f63588.png)
    
## 6.2 Bike Trip vs Age & Gender
    Looking at the gender proportion of the bike users, we can see from the Graph below, that the majority of the 50 year old users are of 'unknown' gender. 
    Furthermore, lokking at the next higher user age groups, we can see that the portion of male users aremore than double than the female users, in fact
    this trend is valid for all age groups.
![image](https://user-images.githubusercontent.com/85843030/134781741-50835685-bcb2-4944-bb66-539815dd4583.png)
    
    

   
