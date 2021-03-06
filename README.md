# COVID-19-VISULIZATION-AND-ANALYSIS
The COVID-19 is a contagious coronavirus that hailed from Wuhan, China. This new strain of virus has striked fear in many countries as cities are quarantined and hospitals are overcrowded. This dataset will help us understand how COVID-19 is spread in Iran and generally aroud the world .

I tried to use a valid and verified dataset to visualize the data, after all, it doesn't matter how good the analysis is if the data is not accurate. Information about the dataset is addressed later on. In this notebook the goal is to show the exact details about confirmed cases,  recovered and also deaths due to COVID-19, data is mostly splitted country wise with an emphasis on, my country of birth,  Iran, and comparing its situation to other similar countries. unfortunately, there are only a few reports on Iran's different cities and no uniform and valid dataset.

## Inspiration

I believe that epidemic data should be openly available and easily accessible for health professionals and data scientists. This dataset would serve as a starting point for people to gather more data about epidemics, not just statistics, but also new stories, government responses etc.

## project Details

I tried my best to display the data in the best way possible, using different variants and types of graphs ( Over 15 different types), data is visualized and analyzed. I started from simpler graphs like bar charts and histograms to more complicated ones like box charts and bubble charts.

There is a brief overview of different types of charts in the image below :

![alt text](https://github.com/prishitakapoor/COVID-19-VISULIZATION-AND-ANALYSIS/blob/main/graphs.png)


## Available Files


* > [COVID-19_Analysis_and_Visualization.ipynb](https://github.com/prishitakapoor/COVID-19_Analysis_and_Visualization/blob/master/COVID-19_Analysis_and_Visualization.ipynb) - This is original notebook with all the explanations and useful data.(You should download and install requirements as instructed on the notebook to see the plots properly)

* > [COVID-19_Analysis_and_Visualization.html](https://github.com/prishitakapoor/COVID-19_Analysis_and_Visualization/blob/master/COVID-19_Analysis_and_Visualization.html) - This is a HTML view of the notebook (You may use it because github can't show the interactive graphs properly at the moment).

* > [NB Viewer Version](https://nbviewer.jupyter.org/github/prishitakapoor/COVID-19_Analysis_and_Visualization/blob/master/COVID-19_Analysis_and_Visualization.ipynb) - This is a 3rd-party website that can help you to see the notebook on the fly, no need to install or download any packages.


## Data

The data used in this project is from a github repository [covid_19_jhu_data_web_scrap_and_cleaning](https://github.com/imdevskp/covid_19_jhu_data_web_scrap_and_cleaning) data is gathered from several verified websites using scrapping, you can see more specific details and python codes that used to scrape the data is available in the mentioned repository. Moreover, there is a list that explains the different files inside the input folder :

   
* > *covid_19_clean_complete.csv* - Country wise day to day cases dataset  

* > *full_grouped.csv* - Day to day country wise no. of cases (Has County/State/Province level data)  
* > *country_wise_latest.csv* - Latest country level no. of cases  
* > *day_wise.csv* - Day wise no. of cases (Doesn't have country level data)  
  
* > *worldometer_data.csv* - Data from https://www.worldometers.info/about/
   
* > *time_series_covid19_confirmed_global.ipynb* - Has day to day global confirmed cases data  
* > *time_series_covid19_deaths_global.ipynb* - Has day to day global deaths data  
* > *time_series_covid19_recovered_global.ipynb* - Has day to day global recovered data  
    
    
### worldometer data
* According to worldometer 
> "For the COVID-19 data, we collect data from official reports, directly from Government's communication channels or indirectly, through local media sources when deemed reliable. We provide the source of each data update in the "Latest Updates" (News) section. Timely updates are made possible thanks to the participation of users around the world and to the dedication of a team of analysts and researchers who validate data from an ever-growing list of over 5,000 sources." - https://www.worldometers.info/about/
