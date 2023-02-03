# **Evaluating Weather**

A large sample of cities across the world were evaluated to determine trends in temperature, humidity, wind speed, and cloudiness compared to the latitude.

All cities analyzed are represented below. The larger circles mean higher humidities.

![bokeh_plot (1)](https://user-images.githubusercontent.com/116215793/216673726-af6db377-262e-4d00-8a9f-8353261a661d.png)

## **Temperature**

Temperatures are higher towards the equator, with signifcantly lower temperatures in the Northern Hemisphere as compared to the Southern Hempisphere.

![Fig1](https://user-images.githubusercontent.com/116215793/216672250-a65730e6-b994-4103-a06c-e7e927a4803f.png)

## **Humidity**

Humidity trends higher as the latitude goes up, meaning that the humidity tends to be higher further north. There is a large grouping of areas just north of the Equator, however, that have low humidity levels. 

![Fig2](https://user-images.githubusercontent.com/116215793/216672719-2e6b9d22-6ae0-4527-8397-4024d90e2852.png)




## **Cloudiness**

The amount of cloud cover increases slightly as one moves north, although the correlation in the data is weak-moderate. There are clusters of locations where the cloudiness is at 100% and clusters where the cloudiness is at 0%. These areas do not seem to be correlated directly to latitude, as some of the areas even overlap each other.

![Fig3](https://user-images.githubusercontent.com/116215793/216673071-2780e216-d79d-4f4c-a334-3773dbe3ac4d.png)

## **Wind Speed**

There is very weak - weak correlation between Wind Speed and latitudes. This evaluation should not be used to predict wind speeds.

![Fig4](https://user-images.githubusercontent.com/116215793/216673175-93cc801f-a372-451a-a1a5-199e47536fa1.png)


# **Determining Ideal Vacation Locations**

The data was filtered to only include ideal weather locations. The weather conditions used are listed below, and users can change these variables within the script if a different set of criteria are desired. 

![image](https://user-images.githubusercontent.com/116215793/216674235-b2bac12b-2e65-4723-a250-813fa7865afd.png)

These criteria led to a remaining 109 potential cities. All cities were located in the southern portion of the Northern Hemisphere, or throughout most of the Southern Hemisphere. 

The 109 cities were then evaluated for hotels located within 10,000 meters (10 kilometers). All cities without nearby hotels were removed from the dataset, leaving 83 viable vacation locations.

![image](https://user-images.githubusercontent.com/116215793/216675348-363c9d60-9982-45c7-a058-1bd132e0f873.png)


