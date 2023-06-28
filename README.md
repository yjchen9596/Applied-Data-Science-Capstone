# Applied-Data-Science-Capstone: SpaceX Launch Analysis 


SpaceX revolutionizes the space industry by offering Falcon 9 rocket launches for $62 million, significantly lower than competitors' prices. 
This remarkable cost reduction is achieved through the innovative practice of reusing the first stage. 

In this project, our goal is to predict the landing success of the first stage, enabling accurate cost estimation for rocket launches. By analyzing historical data and applying machine learning algorithms, we aim to develop a predictive model that can be used for competitive bidding against SpaceX. 
Additionally, we consider the geographical significance of launch sites, which are strategically located near coastlines and the Equator line to optimize trajectories and facilitate access to various orbital inclinations. 

This project can provide valuable insights for the industry, empowering decision-makers with precise cost estimates and enhancing bidding strategies.

## Introduction
- SpaceX offers Falcon 9 rocket launches at an unbeatable price of 62 million dollars.
- Competitors charge over 165 million dollars for similar services.
- The cost reduction is made possible by SpaceX's groundbreaking approach of reusing the first stage of their rockets.
- This innovation has transformed the economics of space travel.

![](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/blob/main/gif/landing_1.gif)

## Data Collection And Data Wrangling Methodology:

- API
- Web Scrabbing from Wikipedia
- Create a new column ‘Class', 1 for success, 0 for fail

  ![](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/blob/main/gif/crash.gif)

## EDA with visualization results:

**Launch Sites Success Rate**

CCAFS LC-40: 26.9% (Florida)

CCAFS SLC-40 : 42.9% (Florida)

KSC LC-39A : 23.1% (Florida)

VAFB SLC-4E : 40% (California)

![image](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/assets/91562548/c8243d3e-1cca-4008-bc56-7b91897d2548)

![image](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/assets/91562548/09acb9f8-a53c-4382-99ef-d847167e4157)

![image](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/assets/91562548/30a8f77d-3f38-451a-916d-d6dcda025e78)

![image](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/assets/91562548/dbb117c1-cbb2-4747-bea8-2f2780adcaeb)

## EDA and interactive visual analytics methodology:
- Folium for interactive map analysis
- Plotly for interactive visual analysis (pie and scatter plot)

![image](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/assets/91562548/2f91bb4f-da1f-4718-98a0-8ba248648d16)
![image](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/assets/91562548/bdca553d-8dba-433a-a650-2311d93fde68)


## Predictive Analysis Methodology 
- Create a column for the class
- Standardize the data
- Split into training data and test data
- Find the best hyperparameter for **SVM**, **Classification trees** and **Logistic Regression**.

## EDA with SQL(ite)
![image](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/assets/91562548/dc88b8a8-4081-433f-ba8c-a999cf995da8)


## Interactive map with Folium
![image](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/assets/91562548/d88b5705-7275-4e9c-9cfe-57f961313f9e)

## Plotly Dash dashboard
[Click Here for Checking the App](https://yuka-chen-spacex-launch-records-dashboard.onrender.com/
)


![image](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/blob/main/gif/dashboard.gif)



## Predictive Analysis (Classification)
- Three methods all have 83.33% accuracy
![image](https://github.com/yjchen9596/SpaceX-Launch-Analysis-Applied-Data-Science-Capstone/assets/91562548/2166d3f4-1c19-4a00-8599-68321cecbc20)


## Conclusion

**Proximity to coastlines:**
   - Allows for safer abort scenarios and emergency contingencies during launch.
   - Simplifies transportation logistics for rocket components.
   - Facilitates integration and assembly processes.

**Proximity to the equator:**
   - Provides an inherent velocity boost from the Earth's rotation.
   - Reduces the amount of fuel required for achieving orbit or reaching destinations.
   - Increases payload capacity or extends the operational lifespan of satellites.
   - Enables access to a wider range of orbital inclinations.
     
** Strategic advantages:**
   - Maximizes operational efficiency and safety.
   - Enhances payload capabilities.
   - Offers flexibility and versatility for space missions.




