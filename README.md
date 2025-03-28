# problem 
Public transportation plays a vital role in urban mobility for most Singaporeans. In 2023, an average of 7.2 million passengers relied on public transport in Singapore, with about 3.24 million passengers using the MRT system everyday (Romero L., 2025), highlighting its significance in the daily commute and economic activities. 

![image](https://github.com/user-attachments/assets/b1459d4c-b1f5-426e-ae24-87214cc533fb)
(Singapore Department of Statistics, 2024)

The filled map above shows the spread of resident population around Singapore as of June 2024. From the map, areas that are densely populated are mainly Jurong West, Woodlands, Seng Kang, Tampines and Bedok. 

![image](https://github.com/user-attachments/assets/9f7ba709-b8ec-4eb1-b599-c7a0cd4d3252)
(Singapore Department of Statistics, 2024) 

As we examine the population distribution of residents aged 65 years and above, we observe that a significant portion of Singapore, particularly the central to southeastern and western regions, has a high proportion of senior citizens. These areas include mature estates such as Bedok, Marine Parade, Queenstown, Toa Payoh, and Bukit Merah, where many long-term residents have aged in place.

Notably, as we compare the two graphs, the Bedok region has a high population density accompanying with more than 20% of population aged > 65. This suggests a need for an effective transportation system that addresses the needs of senior citizens and dense population in Bedok while providing accurate data for commuters to plan their daily route efficiently. 

Current solution:
Currently, there are many applications providing real time bus services updates like Mytransport.SG and Singabus, allowing commuters to plan their route based on bus arrival times. However, many commuters have expressed frustration over the inaccuracy of bus arrival times, which have led to long waiting times and inconvenience. If this issue is not resolved, it will be particularly significant for elderly commuters, who may have difficulty navigating and understanding unreliable transport schedules, while facing mobility challenges and longer travel time. 

# Problem Statement
With that, how can real-time transportation data be optimized in Bedok to enhance the accuracy, accessibility, and reliability of public transport, particularly for the growing elderly population, while ensuring a smooth and efficient commute for all residents?

By addressing these challenges, a smarter, more responsive transport system can be developed utilizing real time bus service data, to support Bedok’s aging community, reduce waiting times, and improve the overall commuting experience for all travelers.


# Project Overview
This project focuses on developing a data pipeline to extract real-time transport data from Singapore's LTADataMall API:https://datamall.lta.gov.sg/content/datamall/en.html

The goal is to extract real-time bus arrival data from the eastern region of Singapore, specifically Bedok, using a data pipeline built with Alteryx. In this pipeline, the data is extracted, transformed into a readable format, and exported as a spreadsheet saved to a local directory.

The extracted data will then be analyzed, and a user interface for a bus arrival app will be constructed using Streamlit. This app aims to provide accurate and accessible bus arrival information to enhance the commuting experience, particularly for the elderly population, by reducing waiting times and improving the overall reliability of public transport services.


# Final Solution 
![image](https://github.com/user-attachments/assets/999cbed8-8d46-4327-8876-66734e0b0f63)
^ final data pipeline developed using Alteryx



Check out the Streamlit app here:
https://bus-arrival-app-ikmt5bqb7jkfv3d3ktrevl.streamlit.app/
