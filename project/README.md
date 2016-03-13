Calculating shortest path in live traffic
=========================================

OVERVIEW
--------

We can notice that a large amount of traffic data is getting generated daily from the navigation systems. We need an accurate system which can analyze live traffic data and compute shortest possible distance to the destination for the drivers. A promising methodology is to give the server a chance to collect live activity data and after that supply them over radio or wireless system. This methodology has amazing adaptability with the number of users. Along these lines, we build up another system called Live Activity Data (LAD) which empowers drivers to rapidly and successfully gather the live traffic data on the broadcasting channel.

DATA
----

We are going to use traffic data available from the Chicago traffic tracker section in data.gov where this dataset contains the historical estimated congestion for 1270 traffic segments. We are going to use MySql to work with database activity and Java for writing business logic to calculate shortest possible destination.

[Chicago Traffic Tracker / City of Chicago / data.cityofchicago.org](http://catalog.data.gov/dataset/chicago-traffic-tracker-historical-congestion-estimates-by-segment-2fdbf)

RESEARCH QUESTIONS
------------------

a. How can be the server periodically updates the travel times on these paths based on the latest traffic, and reports the current best path to the corresponding user.

b. How can we find the dynamic shortest path using the traffic data that change frequently?

CODE AND APPLICATION
--------------------

The code is in Github and instructions are in the README.md file.
<https://github.com/manjukr57/Section1-Project-Group2>

PROJECT MANAGEMENT
------------------

Our project team consists of three members, Manjunath Kuruvadi, Chinna Babu Sadam and Ananjay Mishra.

PROJECT TEAM, DELIVERABLES AND CHECKPOINTS
------------------------------------------

### TEAM

| Team member        | Roles and skills | Contributions |
|--------------------|------------------|---------------|
| Manjunath Kuruvadi | Team lead and code development | Updated the project proposal, analyzed the available traffic data and working on coding part. |
| Chinna Babu Sadam | Works on testing | Cleaning of data and eliminated some of the bad data |
| Ananjay Mishra | Installation and setup | Finished installing and setting up the environment required to test our project outcomes.|

### DELIVERABLES AND CHECKPOINTS

| Checkpoint date | Expected Deliverable | Responsible team member(s) | Checkpoint Results |
|--------------------|------------------|---------------|-------------|
| 2/22/2016 | Finished analyzing data | Manjunath | Found some bad data and asked my team mate to remove that data during cleaning process |
| 2/28/2016 | Cleaning of data | Chinna Babu Sadam, Ananjay | Cleaning process finished and some of the bad data has been removed. |
| 3/8/2016 | Installation and setup | Ananjay, Manjunath | Worked on setting up the environment and chosen Java, MySql to implement this project. Also started coding. |
