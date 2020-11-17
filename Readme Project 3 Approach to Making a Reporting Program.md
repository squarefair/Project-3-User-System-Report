I see that there is a request for me to make a program that will track certain occurances in a documentation system. I think I will use a stack data structure. From top to bottom the procedurs would be suspicious activity, irresponsible behavior, system glitch, domain count, and additional insights. I will need to import/ open the user log to analyze using my program. As for functions I will be using, I will need to use if statments for all of the 5 activites needed to be recorded, if statments are the start of making a program. I will need to use else statements when a user is doing suspicious or iresonsible things (when they go out of the time frame). I think it would make thing easier if I used def to make these 5 report features, for example def suspicious_report.txt:. I would define these five things in diffrent cells. For domain count I will need to  use .read . For system glitches, those will be included in else statements. Of course I will need print statements to display the log after the information has been processed. As for additional insights I will try to make those later.

This program is going to need at least 4 defined functions. 
The first defenition I need to make is for suspicious activites(suspicious_report.txt). Suspicious activity is when a user logs in between 00:00 hours and 05:00 hundred hours. We are using military time. Logging in 5 times in one day is also going to be considered suspicious activity.

The second defention is for irresponsible behavior. This will be defined as logging in more than you log out. Basically fogetting to log out will be named irresponsibe behavior.

The third defenition is going to be for system glitches. This will be defined as a user loggin out more than they log in, This is impossible so it will be called a glitch.

For the fourth defeniton is going to be for domain count. This will display a users email ID, name, and domain name.
It has come to my attention that the 5 defenitions must each produce a report. So I will need to put each defenition in its own cell.
These reports will need to produce text files.

This task seems more intricate than I thought. Something key to making this program work is line.split. I need to get each column read. I also needed to close the files after I make them to prevent further writing and complication.


The first issue I had was splitting the columns apart in the userlog. This was solved by doing line.split(" ")

The second issue I had was labeling each category. Iw as able to do this by using dictionaries and labeled time = 0  , activity = 1, server = 2 , email = 3. The numbers coresponed to column from left to right.

A third issue I ahd was making the military time function for suspicous activities. TO be hines I do not know if it still works. I tried to make the taboo time slot from midnight to 5 am. I used midnight as zero and  five am as five.

