2nd Line : General Description of the file
3rd Line : 1 If the(cost and travel time) graphs are complete and 0 if not
4th Line : List of kinds of vehicles separated by semicolon
5th Line : List of localizations(including depots) separated by semicolon. Each localization is described as follow(separated by comma):
		#number of localisation(identification)
		#type of localization : "1" if it is a depot and "0" otherwise
		#name of the localization
		#address or coordinates : empty by now
6th Line : List of requests/customers to be planned separated by semicolon. Each request is described as follow(separated by comma):
		#number of the request(identification)
		#identification of the request localization
		#the number of kinds of vehicles capable to handle the request
		#the different kinds(identification) of vehicles separate by ":"
		#the different duration of execution of the request for each specified kinds of vehicles separated by ":"
		#the start time of the request(time window): defined in minute, like 7h30 is 7*60+30
		#the end time of the request(time window)
7th Line : List of Vehicles separated by semicolom. Each vehicle is described as follow(separated by comma):
		#number of vehicle(identification)
		#identification of the starting depot
		#identification of the ending depot
		#name of the vehicle
		#kind (position) of the vehicle
		#Starting working hour
		#Ending working hour
