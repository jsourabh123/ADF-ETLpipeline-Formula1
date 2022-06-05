# Formula1-data-analysis
Download data from https://ergast.com/mrd of Formula1 from year 1954 to 2021. Upload the data to Azure blob storage and use it for analysis and ETL pipeline creation in Azure Data factory.
We are using 8 different dataset out of which four are Incremental load on weekly basis.Also,we are transforming and generating into 4 different deltalake files.
The Ingestion datasets schema are give below:-
![image](https://user-images.githubusercontent.com/43174715/172060368-e0ea7c13-2d03-4cae-ac0f-a9e1960b4a48.png)
![image](https://user-images.githubusercontent.com/43174715/172060452-536faafe-fe9d-4cae-9813-f3c61611c009.png)
![image](https://user-images.githubusercontent.com/43174715/172060473-cbd83f2d-7479-42d5-98a8-6d8ae9e08876.png)
![image](https://user-images.githubusercontent.com/43174715/172060488-0097ab10-45e6-4d64-b6ab-eeb15821a0cf.png)
![image](https://user-images.githubusercontent.com/43174715/172060521-fc6909ad-c929-4635-9a0a-cd886c2b6435.png)
![image](https://user-images.githubusercontent.com/43174715/172060543-356fe8b5-83ea-4321-863c-fdb4aec5a382.png)
The transformation dataset schema are given below:-


