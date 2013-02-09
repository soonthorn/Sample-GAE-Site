# GAE Gaia Framework
sample site at http://sample-gae-site2.appspot.com

## How to solve google appengine error - Another transaction by user already in progress for app
The following error occurs in google app engine
Another transaction by user already in progress for app
In this post i'm  going to explain how to solve the app engine error

*step1: open command  prompt  

*step2: navigate  to   C:\Program Files\Google\google_appengine

*step3: enter   the  following  command

appcfg.py rollback  C:\Users\subash\Desktop\vs

note(appcfg.py  python file inside  C:\Program Files\Google\google_appengine

C:\Users\subash\Desktop\vs  --  your project directory)