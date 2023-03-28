# Data Fellowship 9 Session 5: Data Visualization Assignment
Creating a Dashboard via tools (Looker, Metabase, etc) with the yellow taxi trip records 2019 https://www.kaggle.com/datasets/microize/newyork-yellow-taxi-trip-data-2020-2019?resource=download.
## Tech Stack
- BigQuery
- Looker Studio
## Setup
1. Ingest the data from https://www.kaggle.com/datasets/microize/newyork-yellow-taxi-trip-data-2020-2019?resource=download to our BigQuery,

![image](https://user-images.githubusercontent.com/124119569/225218149-3280c7f1-502e-42c1-99ff-22013e9863b5.png)

2. Open https://lookerstudio.google.com/u/0/navigation/reporting then create report,

![image](https://user-images.githubusercontent.com/124119569/225218314-2a469859-c045-4df1-b548-089ebab848c9.png)

3. Add data to report via Big Query,

![image](https://user-images.githubusercontent.com/124119569/225218434-352718f4-3e54-4e1c-b225-4f918a9e903a.png)

4. Choose the table which have already been created in BigQuery,

![image](https://user-images.githubusercontent.com/124119569/225218582-33f27354-674a-4efb-937f-e34107a6a20b.png)

5. Then create the dashboard,

![image](https://user-images.githubusercontent.com/124119569/225218812-47301457-f712-42fa-981a-00e82896e8a2.png)
## Result
This is the result of a [dashboard](https://lookerstudio.google.com/reporting/514eea45-3c6a-49aa-ae07-3e4c56512581) I made from yellow taxi trip records 2019. I made two scorecard which explain the total of the passengers count and total trip distance from January until March and also a line chart which shows the everyday total passenger count and total trip distance.

![image](https://user-images.githubusercontent.com/124119569/225219304-aaa2f762-ffdb-4fc2-89b5-dcd8c26cfc13.png)
