# NYC Citi Bike Analysis
## Module 14: NYC Citi bike with Tableau

## Overview and Purpose

- The primary objective is to convince investors that a bike-sharing program in Des Moines, Iowa is a lucrative and solid business proposal. To solidify the proposal, one of the key methods is to analyze existing data from New York City and create a customer/user Bike Trip Analysis.
- For this analysis, I used Pandas to change the "trip duration" column from an integer to a datetime datatype. Then, using the converted datatype, I created a set of visualizations with the following objectives:

1. Show the length of time that bikes are checked out for all riders and genders.
2. Show the number of bike trips for all riders and genders for each hour of each day of the week.
3. Show the number of bike trips for each type of user and gender for each day of the week.
4. Finally, I will add these new visualizations two I created earlier this year for my final presentation and analysis to pitch to investors.

## Resources

- Data Source: From the public data source at  Citi Bike System Data page: https://ride.citibikenyc.com/system-data
- Downloaded CSV  Text file for analysis: "201908-citibike-tripdata.csv.zip"
- Software: Tableau Desktop version 2021.3, Jupyter Notebook, Anaconda Prompt, Python 3.9

## Results

### Tableau Public Story: [Link to Dashboard](https://public.tableau.com/app/profile/said.husseini/viz/NYCCitiBikeAnalysisModule14Challenge/NYCCitibikeChallengeAnalysis) 

### Total rides in the month of August for NYC Cit Bikes
![Total Users](https://user-images.githubusercontent.com/88692025/144160951-262f39ce-dc06-423b-8757-1376925a2a5c.PNG)
- An impressive statistic of 2.5 million rides, quite a bustling city!

### NYC Citi Bike Users by Gender
![Users by Gender](https://user-images.githubusercontent.com/88692025/144160520-032bd370-0bcc-495e-9799-a86a17e470c0.PNG)
- The Gender Breakdown for Citi Bike users within the month of August in New York City, the analysis shows that the majority of users self-identify as Male, 65% of the total user base. No real takeaways here unless it is possible to specifically target male users in future cities for more usage and revenue.

### NYC Citi Bike Customer Type
![Users by Type](https://user-images.githubusercontent.com/88692025/144160705-0e11b486-6584-4d8b-be89-163bb2da7fd5.PNG)
- A good sign for this Citi Bike business in NYC, most users are revenue stable Subscribers that give a steady income to the bike sharing company. A staggering 81% of users.

### Top Starting Locations
![Top Starting Locations](https://user-images.githubusercontent.com/88692025/144161505-010cab2f-35d6-4089-b68f-8d90c034c0c4.PNG)
- Logically, the most densely populated region in SOHO and Manhattan with the most tourism, offices and high rises has the largest concentration of starting locations, a useful insight for any city looking to replicate the Bike sharing standards of NYC.

### Checkout Times for Users
![Trip Duration](https://user-images.githubusercontent.com/88692025/144161837-2113d3b5-c6c8-4f66-b218-8f8b72e2fe0b.PNG)
- Checkout times seen here within the first 3 hours of starting a ride.
- An overwhelming majority of Citi Bike trips are below the 1hr and 30-minute mark.

### Checkout Times for Users by Gender
![Trip Duration by Gender](https://user-images.githubusercontent.com/88692025/144162007-70f2e7d1-4012-411b-b977-02e56edb1fcd.PNG)
- Checkout times seen here within the first 3 hours of starting a ride by self-identified Gender.
- Of the entire Citi Bike user base, Males tend to use bikes for longer than Females within the first hour. 

### Trips by Weekday per hour
![Stop Time Heatmap](https://user-images.githubusercontent.com/88692025/144162326-5c74dba0-032a-43ea-86bf-7389d59c9736.PNG)
- Bike Usage heatmap shows that most usage is concentrated in the 6-9AM and 3-6PM timeframes in line with NYC commuting and office work schedules.
- Most frequent trips occurred on Thursdays in August.
- Wednesdays least popular day of the week.

### Trips by Weekday per hour by Gender
![Stop Time by Gender](https://user-images.githubusercontent.com/88692025/144162456-a6dff32e-f496-407f-84d4-f35786fb22f5.PNG)
- From this heatmap we can determine that Males contributed the most during the rush hour commuting period.
- Wednesdays least popular day of the week by any Gender split.

### Trips by Weekday by User Type and Gender
![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/88692025/144162590-3f481380-57e5-4732-9f74-ad8c61473fe6.PNG)
- This heatmap shows the majority of Citi Bike users in NYC are subscribers and of those Subscribers they are pre-dominantly self-identifying as being Male.

## Summary

To conclude the results of the analysis, there is a strikingly high number of users of the Citi Bike sharing program in New York City in the month of August 2019. The majority of users were subscribed to the program and were self-identifying Males. The most concentrated are of start and stop times was in the central Manhattan area where there is an abundance of traffic and standstill cars and buses. The majority of users use the service to commute to and from work.

## Recommended Further Analysis:

1. Analyze an entire year worth of data to get more of a feel if this kind of project works in colder months. So, a further visualization for the month of December with the exact same metrics as August would be an example.
2. Another visualization that would be useful is to look into which location have the most damaged bikes to focus repair efforts on these bikes. So, a visual of the start and end location vs the number of times repaired.
3. Lastly, a visualization to show locations of commuting times like 6-9AM and 3-6PM to determine where more bike stations are needed or more repairs or bikes are needed. and inversely an analysis that shows which locations are underused and thus wasted.
