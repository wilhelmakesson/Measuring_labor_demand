# Measuring labor demand through Job Ads

Labor demand is a difficult thing to measure. Right now, the most common way is to send out surveys to employers asking them what labor skills they need. This project aims to gauge labor demand by downloading job ads from job platforms, and use this as a measure of changes in labor demand. 

This index of digital job ads will be constructed based on the Swedish job platform Arbetsförmedlingen, and compared to the Quarterly labor demand survey produced by the Swedish statistical agency SCB. Finally, the index will be complemented with web scraping job ads from other platforms.

## Main project parts

The project will go through the following steps:

 - Download all job ads from the Swedish job platform [Arbetsförmedlingen](https://arbetsformedlingen.se/) using [Jobtech Development](https://jobtechdev.se/)
 - Clean data and convert into SQlite database
 - Analyze seasonal component and cointegration of final time-series index using LOESS and Engle-Granger tests
 - Analyze relation to Statistics Sweden's quarterly survey using OLS
 - Add concluding remarks on usability 
 
 ## Contact information
 
 Wilhelm Åkesson - wilhelm.akesson@macrobond.com
 
