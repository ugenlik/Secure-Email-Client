Umut Can Genlik
ugenlik1@binghamton.edu


-----------------------------

Secure Imap Client App.
-----------------------------


This is a Java Application connects to an imap server by using text inputs from users that contains host name, username and password. 
When Connection establishes application first send to server ". login username password" command that username and password has already taken from user.After sending command to server, server replies application's request and when application get positive respond it send ". fetch " command to take information about date, header and body information from user. 
Application uses an algorithm to parse information from server and it screens parsed data to screen with mouse clicked event so that user can choose desired email and see the body of email.

____________________________

Used Swing Widgets

-----------------------------

3 jtextfield, 2 jbutton, 1 Jlist and 1 textarea

----------------------------
Additions
-----------------------------

Application doesn't save user and password 