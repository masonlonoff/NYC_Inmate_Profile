# NYC Inmate Profile
![image](https://github.com/masonlonoff/NYC_Inmate_Profile/assets/117112918/63c406d4-e843-4e04-be92-ecfe07486dce)



## File Descriptions 
* [Crime_EDA](https://github.com/masonlonoff/NYC_Inmate_Profile/blob/main/Crime_EDA.ipynb): This file contains data cleansing in pandas and SQL as well as column-level EDA.
* [Dataset_Insights](https://github.com/masonlonoff/NYC_Inmate_Profile/blob/main/Dataset_Insights.ipynb): This file contains 29 queries related to the dataset. It also includes a Table of Contents for ease of use.

### Table of Contents:

- [Description](#description)
- [Dataset Information](#dataset_information)
- [Objectives](#objectives)
- [Acknowledgement](#acknowledgement)
- [Disclaimer](#disclaimer)


### Description
Daily inmates in custody with attributes (custody level, mental health designation, race, gender, age, leagal status, sealed status, security risk group membership, top charge, and infraction flag). This data set excludes Sealed Cases. Resulting summaries may differ slightly from other published statistics.

Agency:	Department of Correction (DOC)
Date Created: March 23, 2016
Category:	Public Safety


### Dataset_Information
- **INMATEID** - This is the primary key column that uniquely identifies each inmate record.
- **ADMITTED_DT** - This field has the admitted date and time of the incident.
- **DISCHARGED_DT** - This field has the inmate discharged date and time.
- **CUSTODY_LEVEL** - This has the level of cutody provided for the inmate. Values are MIN,MED,Max custody levels.
- **BRADH** - BRADH has values Y or N. The inmate is under mental observation.
- **RACE** - Race of the inmate.
- **GENDER** - Gender of the inmate (Male or female).
- **AGE** - Calculated Age of the inmate.
- **INMATE_STATUS_CODE** - provides the inmate status example if an inmate id a detainee.
- **SEALED** - Sealed=Y implies that the inmate information is not to be shown in public.
- **SRG_FLG** - SRG_FLG=Y means that the inmate is an approved gang affiliation.
- **TOP_CHARGE** - Top charge for the inmate.
- **INFRACTION** - Indicates whether the inmate has infraction.


### Objectives
1) Understand the underlying characteristics of the dataset
2) Utilize Pandas and SQL to prepare the dataset for analysis
3) Conduct Column-Level EDA 
4) Write queries to answer dataset related questions


### Acknowledgement
This dataset was taken from [NYC Open Data](https://data.cityofnewyork.us/Public-Safety/Daily-Inmates-In-Custody/7479-ugqb)



### Disclaimer
From the website: "This data set excludes Sealed Cases. Resulting summaries may differ slightly from other published statistics."
