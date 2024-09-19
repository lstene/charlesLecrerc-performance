## Project Background

---

Since his debut in 2018, Charles Leclerc has become a prominent figure in Formula 1, competing at the highest level with Ferrari. This project delves into Leclerc’s performance across multiple seasons, races, and conditions, utilizing extensive data from FastF1 to provide in-depth insights and recommendations.

The analysis aims to uncover trends, strengths, and areas for improvement in Leclerc's performance, helping stakeholders, such as teams and analysts, better understand his racing dynamics and competitive edge.

Key insights and recommendations are provided across the following areas:

- **Race vs. Qualifying Performance:** A comparison of Leclerc's results in qualifying sessions versus races, highlighting where he excels and where potential gains can be made.
- **Weather Condition Analysis:** An evaluation of Leclerc's performance under varying weather conditions (dry, wet, and mixed), emphasizing his adaptability.
- **Circuit Type Analysis:** A study of his performance on different circuit types, including street circuits, permanent tracks, and hybrid circuits.
- **Fastest Lap Achievement:** Analysis of Leclerc's success in securing the fastest lap in races, and its contribution to overall race strategy.

## Data structure & Initial Checks

---

FastF1 API retrieves data as Json format and it can be made according to what to retrieve into a single query and made the data frame scheme like this:

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ffd29d6c-74da-4c04-b4b4-a11f5a89a3a9/fc97c208-0229-4be1-ac19-6d8da05e8e7d/image.png)

Prior to the  beginning the analysis, a variety of checks were conducted for quality control and familiarization with the datasets. The Py Spark queries utilized to inspect and perform quality checks can be found here.

## Executive Summary

---

### Overview of Findings

Besides his rookie season with Sauber, Charles Leclerc has shown a steady performance in all of his seasons. With standout performances in the 2019 and 2022 seasons, where he achieved the highest points totals of his career during these two seasons.

Also in across his career he has managed to earn various points in most of the races. This makes sense according to his average position of 8th position on race, making him a sure bet in making points for the team and himself. However, he doesn’t has numerous fastest laps during his career.

The following sections will explore additional contributing factors and highlight key opportunities for improvement.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ffd29d6c-74da-4c04-b4b4-a11f5a89a3a9/0ec2f781-6d9d-472e-ae05-dcd349da6bfe/image.png)

### Qualifying position vs race position

- Leclerc tends to perform better in qualifying than in the races. This discrepancy can be attributed to various factors, including the car's performance. Let’s remember that since his debut he had never been on a dominant team and Ferrari has been struggling with recovering their level race after race.
- On average, Leclerc tends to lose around two positions between qualifying and the race. This drop can result in a significant loss of points, especially when these positions are lost from the top 5, where the points difference between places is the most substantial.
- The best season was 2022 were he managed to keep almost the same position between race and qualifying. This could be explain with the change of regulations given by FIA for the cars were Ferrari made a really good job that couldn’t keep up with the bad race strategies

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ffd29d6c-74da-4c04-b4b4-a11f5a89a3a9/b89d19ed-9e5a-4181-98c5-578355d63d48/image.png)

### Performance by Type of Circuit

- The best type of circuit for Charles are the hybrid circuits which are a combination of street streets and tracks built for the race. Here he achieves an average of 6th or 7th position, an improvement from his overall.
- Charles also has a good performance in the urban circuits like Monaco or Azerbaijan. Even though it’s the type of circuit were he loses most position (2 positions) he gets almost the same points that in the hybrid circuits.
- Permanent circuits make up the majority of tracks on the Formula 1 calendar, yet they are where Charles Leclerc tends to perform the worst. This could explain why he loses a significant number of points over the course of the season and highlights an area where he should focus on improving. Addressing his performance on these types of circuits could significantly boost his overall results and points tally.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ffd29d6c-74da-4c04-b4b4-a11f5a89a3a9/e4a28d63-a544-485a-b907-c55c3e1c9b8e/image.png)

### Performance in different weather conditions

- The majority of races on the Formula 1 calendar take place under dry track conditions, where Charles Leclerc tends to perform better. In these conditions, he averages 8 points per race, typically finishing in 7th place.
- In wet or mixed track conditions, his performance is relatively similar, with an average finishing position of 9th. However, Leclerc has scored more points in full wet conditions. This could be attributed to strategic errors, particularly in timing tire changes from wet to dry, which can negatively impact his results.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ffd29d6c-74da-4c04-b4b4-a11f5a89a3a9/ff5f3edf-15f4-4e16-8b26-b5696b0ad505/image.png)

## Recommendations

---

- Despite the good performance in hybrid and urban circuits **Charles needs to raise his performance on the permanent circuits** as they give the most points across the season. He should increase his position target to at least 5th in order to achieve better results in the championship
- With a deficit of 2 positions in the race conditions that involves water it seems helpful to improve  the driving abilities in this condition and the race strategies on when change tires so Charles doesn’t loose to much positions that makes him loose points
- Keeping better consistence between the results in the qualifying and the race positions would also make a drastic change in Charles performance as in the last 2 years he averages a 4th position in qualifying that could mean 12 points but instead he averages a 7th position. Meaning he looses 6 points
