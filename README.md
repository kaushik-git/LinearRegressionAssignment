# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
-
- To understand the factors on which the demand for shared bikes depends. Specifically, we want to understand the factors affecting the demand for these shared bikes in the American market:
- Which variables are significant in predicting the demand for shared bikes?
- How well those variables describe the bike demands?
- Dataset Used: Daily rental record from 2018 and 2019

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Significant Features
  - Year
  - Temperature
  - Wind Speed
  - Season (spring, winter)
  - Weather(Rain, Mist)
  - Day (Sunday)
  - Month( July, September)
- Final Equation: cnt = 0.258592 + yr * 0.234574 + temp * 0.449323 + windspeed * -0.141044 + spring * -0.114692 + winter * 0.043831 + Light_Rain * -0.285866 + Mist * -0.079670 + sunday * -0.044329 + july * -0.069784 + september * 0.052198

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- NumPy - version 1.26.4
- Pandas - version 2.1.4
- MatPlotLib - version 3.8.0
- Seaborn - version 0.13.2
- SciKit-learn - version 1.2.2
- StatsModels - version 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@kaushik-git] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
