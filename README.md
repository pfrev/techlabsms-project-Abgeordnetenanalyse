Historical analysis of German parliament MP data
==============================

The project’s goal is the investigation and visual depiction of the German Member of parliament’s historical data since 1949 
in regards to their sex, age, country of birth and party affiliation, as well as the calculation of the probability for a 
representative to be part of the parliament in the next parliamentary period.

Project Organization
```
├── files
|   ├── Cleaning and Extracting.ipynb    -> process of extracting data and cleaning it
|       ├── MdB_Indexed.csv              -> the cleaned DataFrame
|   └── Prediction.ipynb                 -> prediction of future Bundestag composition
|       ├── 20_Bundestag.csv             -> the result of the prediction for the next parliamentary period
|   └── Visualization.ipynb              -> visualization of different propertied 
|       ├── graphs                       -> resulting graphs
|   └── MDB_STAMMDATEN.XML               -> the raw data
```

This project was created as part of a group project in the TechLabs DigitalShaper Program in 2019. TechLabs has made it their mission to educate students in the art of coding for free. They won the Google.org Impact Challenge Germany in 2018, you can find out more at https://www.techlabs.org/.
