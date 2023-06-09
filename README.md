# PJM REAL TIME PRICE PROJECT

https://www.pjm.com/ - Data was downloaded from PJM website and manually merge together. 

In the U.S., we expect reliable, 24/7 access to electricity usage. From the consumer perspective, there is generally no more thought given to electricity usage than simply trying to use less to reduce their utility bill. From the utility perspective, though, ensuring that 24/7 reliability of power requires careful optimization between power generation and power demand, also known as load. Electricity is a unique commodity because supply and demand must be continuously balanced to have a safe and reliable grid. Electricity generation, transmission, and consumption are nearly instantaneous. A utility may be able to fulfill the load in its service area with its own generation, but it can also participate in wholesale power markets, which are split into a day ahead market and a real time market. Wholesale energy prices are expressed as the price for a megawatt of power to flow for one hour. At the day ahead level, utilities have incomplete information on power demand, but will pursue strategies of buying and selling for periods of what they can reasonably expect to be periods of excess power demand or excess power supply, respectively. Additionally, in the day ahead market, the longer time frame of purchasing or selling fixed amounts of power for days, months, or even quarters, allows for strategic planning and resource optimization. 

<img width="815" alt="Screen Shot 2023-04-18 at 4 40 27 PM" src="https://user-images.githubusercontent.com/67845910/232899837-5f104492-64a1-4218-accc-37b69869cbe5.png">



The real time market, on the other hand, has more complete information about power demand because it operates at an hour-by-hour granularity. Therefore, the primary goal of the real time market is to completely fulfill the real time power demand through hourly purchases and sales. While fulfilling this goal, the utility hopes to either minimize cost or maximize profit. Therefore, the ability to predict the real time price for the next hour is critical to decision making for how and where to procure or sell power.  This paper examines several different methods for predicting the real time price of power. We used historic data from the Duke Energy Ohio Kentucky (DEOK) region of the Pennsylvania, Jersey, Maryland Power Pool (PJM), the geographic region surrounding Cincinnati, as a case study to build and test our models. 

The PJM area is a good case study because a wealth of hourly level data is publicly available for day ahead and real time prices, for generation by fuel type, and for MWhs demanded. Also, since PJM is a regional transmission operator (RTO), prices are set generally by market conditions and not influenced by trader decisions such as in bilateral power markets. Thus, the market conditions can be expected to be fully reflected in the settled prices. 


