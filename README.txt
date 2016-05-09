Team members:-
1. Omkar Salvi - 1209536104	
2. Saurabh Jagdhane - 1209572595
3. Vishal Srivastava - 1209824652

###### Fitness application for Everyday use (Project.apk) #####

Note:- 1.Make sure internet connection and GPS of mobile device is TURNED ON.
		2. Make sure mobile device is set to Portrait mode only.
		3. For the mobile devices with Android API 23 and above...Go to settings>apps>Project>Permissions>Storage>ON
		4. For the mobile devices with Android API 23 and above...Go to settings>apps>Project>Permissions>Location>ON
		5. Our path for the Music player is as follows: storage/emulated/0/alarms/fire-flies.mp3
		   Threfore, make sure you create a folder alarms and place fire-flies.mp3 provided along with the project in alarms folder.
		
***Instructions to use:-
1. Enter the user information such as weight, height, age, etc.
2. Get the BMI
3. Go to next activity and select the intended exercise mode (pushups, running, cycling)
4. For running activity (**only for outdoor use),
	Click on START button to acquire current GPS location. Make sure device is attached to the user's arm. 
	This will help differentiate between running and walking. Once this activity is complete click DONE button to stop the activity.
5. Same for cycling exercise mode.
6. For pushups activity,
	First keep the phone on the ground facing user, click start button and start performing the activity. 
	This will count number of pushups using proximity sensor which will be displayed on screen. Once finished click on STOP button.
7. After doing all the activities for the day, click button DONE FOR THE DAY which will save the data such as Calories burnt, Timestamp, distance travelled 
	by the user into the database.
8. Name of the database is: FitnessApp
9. Name of the table is dependent on the user information as Saurabh_22_male.
10. If user wishes to TURN OFF music, Social media integration, vibration notification and context aware suggestion about weather then this features are 	   provided in settings from very first activity.
11. Make a note that alarm volume is dependent on Media volume and not the System ringtone volume.
12. Once alarm is set make sure that GPS and Internet connection is ON at the time of ringing alarm.
	Once the notification is generated it will take to the Weather activity and will suggest user whether to workout in a Gym or Outside.
13. BARGRAPH indicates expected calorie burn and actual calories burnt by user during the exercise per session.

