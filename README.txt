1) def NHTSA_crashes(details):
	- This function requests NHTSA API and provides details of crash data in Pennsylvania 	
	  between the years of 2018-2019
	- To interact with the function:
		NHTSA_crashes("people") -> prints out the amount of people involved in a car accident
		NHTSA_crashes("fatality") -> prints out the amount of fatalities
		NHTSA_crashes("API Data") -> returns the NHTSA Crash Data


2) def PhillyTrafficReport(Report)"
	- This function displays the most recent traffic incident that occured in Philadelphia, requesting from MapQuest API
	-To interact with the function:
		PhillyTrafficReport("type") -> prints our the type of incident, the severity, the date, and details


3) def GetCount():
	- This function is used to find the unique Counties in Pennsylvania to be used in the following function(PACountyData)
	- It does not take any arguemnts for it just returns the list of counties for the user to choose from
	-To interact with the funtion:
		GetCount() -> prints out a unique list of counties


4) def PACountyData(county,details):
	- This function is used to display the specific details for the provided County
	-To interaction with this function, take one of the counties listed from the previous county and add either "cars" or "people" argument:
		PACountyData("PHILADELPHIA (101)" , "cars") -> prints the amount of vehicles invovled in incidents in given county
		PACountyData("PHILADELPHIA (101)" , "people") -> prints the amount of people involved in incidents in given county

	
-One challenge I ran into is that I was unsuccessful in parsing the URL to allow the user to input a specific date range.
-However, it is possible to manipulate the url manually inserting the specific date if the user desires to. 