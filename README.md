# Crop-Price--Prediction
Prediction of prices for the crop Potato in District “Agra” in the state of UP across year 2020.

Problem statement:

Overview: 
There are over 4,000 agriculture markets (commonly known as mandis) in the country. Everyday prices fluctuate in the markets basis supply and demand of the crop. 
Prediction of crop prices is one of the most important task to ensure efficient crop planning and food safety in the country. 

The problem statement revolves around prediction of prices for the crop Potato in District “Agra” in the state of Uttar Pradesh across year 2020. 

Data:

i. The historical data for prices in district “Agra” of state “Uttar Pradesh” are reported daily on Agmarknet. 

ii. Prices for a particular date (say 20 Mar’2021) can be extracted from a URL on Agmarknet: 
https://agmarknet.gov.in/SearchCmmMkt.aspx?Tx_Commodity=24&Tx_State=UP&Tx_District=1&Tx_Market=0&DateFrom=20-Mar-2021&DateTo=20-Mar-2021&Fr_Date=20-Mar-2021&To_Date=20-Mar-2021&Tx_Trend=0&Tx_CommodityHead=Potato&Tx_StateHead=Uttar+Pradesh&Tx_DistrictHead=Agra&Tx_MarketHead=--Select-- 


IDE - Jupyter Notebook
Language - Python

Steps to run the file:

Open the given url for dataset and select the following field,
                                       district => “Agra” , 
                                       Price/Arrivals => Choose Price, 
                                       Commodity => Potato, 
                                       state    =>   “Uttar Pradesh” , 
                                       date from jan 2020 to dec 2020 , 
                                       (Note:- Don't choose market)

Download the data from the url mentioned above(click to 'Export to excel').

Open the Code in Jupyter Notebook.

Upload the zip file on jupyter and run the code.

Note: All the dependencies are imported and if there is any libraries that are not installed then just type "conda install ____(mention libraries that are not installed)". After that import it on the code.

There are two seperate code written for q.a and q.b for better understanding.. 
