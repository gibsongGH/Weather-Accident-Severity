## Weather Impact on Accident Traffic Severity

This project uses weather measurements at the time of accidents to make predictions on the severity of traffic repercussions.

Directory Structure
___________________

Data: The zipped source file.

Notebooks: This directory includes the Notebooks and Code for the main part of the data wrangling, exploration and model generating.

[Notebooks](https://github.com/gibsongGH/Weather-Accident-Severity/tree/master/notebooks)

Reports: This is where you should start. It includes the project report and slides to get an overview of what this project tackles.

[Reports](https://github.com/gibsongGH/Weather-Accident-Severity/tree/master/reports)

**Project Proposal**

*What is the goal?

Is it possible to tell from weather and location information how long the accident traffic will last?

*Who cares?

Current routing applications will offer alternative routes to drivers, and will update destination 'arrival time' based on the speed of traffic movement.  Routing and weather apps may want to provide drivers a suggested time of 'when' to start travel, to avoid accident traffic altogether. 

*What data are you going to use?

The data, US-Accidents: A Countrywide Traffic Accident Dataset, by Sobhan Moosavi et al, can be found at https://smoosavi.org/datasets/us_accidents.  

Data description from website:

This is a countrywide traffic accident dataset, which covers 49 states of the United States. The data is continuously being collected from February 2016, using several data providers, including two APIs which provide streaming traffic event data. These APIs broadcast traffic events captured by a variety of entities, such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road-networks. Currently, there are about 3.0 million accident records in this dataset.

*What is your approach?

Binary classification.  There are four tiers of traffic severity, condense these into Low and High.  Compare a Logistic Regression Classifier to a Random Forest Classifier.

*The Results

The code, notebooks and documentation for this project can be found in this repository. Additionally, slides and a project report can be found in the reports directory.  
