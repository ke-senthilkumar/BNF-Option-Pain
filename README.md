# BNF-Option-Pain

Knowing the Option pain or the strike where the current expiry of option is going to happen is an interesting topic. If one know this value, then a trader can initiate trades based on this value and make some profit.

With the changes implemented by NSE India in their old website (www1.nseindia.com), it was difficult to fetch this via simple web data query. One has to implement cookies and other headers correctly to fetch the data. I have implemented those changes and now it fetches data.

I have also added few charts to display OI, Change in OI and Volume data. There is also a chart which displays Option Pain value over time. If used correctly, this can really alter your trading style.

NOTE: 
1. The data refresh is set to 10 min. One can alter this value from the Data-Connections-<connection>-Properties-Refresh Every .... option. Dont go below 5min, otherwise the exchange might blacklist the IP
2. Sometimes, the data is not fetched and error occurs. This is known issue in the .Net framework. Try to follow the instructions in the Help tab.
