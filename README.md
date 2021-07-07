# VxRail-Log-Explorer
Provided with no license or guarantee.

**Instructions**\
-Install [Power BI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494)\
-Put VxRail 7.x log files in c:\logs\VxRail and click Refresh\
-Select the log file you would like to evaluate\
\
Contact paul.galjan@dell.com with questions and suggestions.

**Overview**\
A tool to quickly visualize VxRail 7.x log files, allowing you to filter by time, microservice and log criticality.  Three views are available:\
\
**Log Explorer**\
A basic, minimally filtered view of the log.\
![image](https://user-images.githubusercontent.com/11296072/124794738-53ecb700-df1d-11eb-95cc-204de999b480.png)\
\
**Python Explorer**\
Filtered to included only entries including Python commands.  There's some SQL to extract the command name, but that seems somewhat sensitive to the log format, so command name extraction doesn't currently work with putty exports\
![image](https://user-images.githubusercontent.com/11296072/124781852-bd66c880-df11-11eb-8389-85acd72ae6ba.png)\
\
**Host Explorer**\
Filters on hostsn, extracts host configuration details & displays complete host JSON parameters if present\
Seems to work with putty-generated logs\
![image](https://user-images.githubusercontent.com/11296072/124799685-d1ff8c80-df22-11eb-9303-bcccfec6685f.png)
