Welcome to jsFiller!
=====================
Your one-click add and test script or stylesheet!

Test it!
-------------

Click [here] [link], and avoid reading any of what's below...

----------


Goal
---------

**jsFiller** is a simple bookmarklet that allows you to very simply test out scripts,libraries, and css stylsheets by either selecting from a list of commonly used(by me) libraries, selecting from cdnjs, or simply inputing the url within the dialog.
It even provides you with nice bookmarklets other people have done for you!


TODO
--------
-Add necessary libs
-create modal
-add tabs to modal



Uses
--------
The library is based on the following frameworks:
- AngularJS for the data handling
- AngularUI for the layout
- Bootstrap for the the design

All three libraries are added to your page to provide the functionality, it is by no means efficient, but this is a dev tool, so I consider this to be ok. Plus, if you already use one of these libraries, it won't make a difference at all.

Thanks
----------
SubtlePatterns for the idea, Bookmarkleter for the syntax, you for reading and using this
Any thoughts, forks, support, ideas, pull requests warmly welcome!

[link]: javascript:(function()%7Bvar%20src%3Dprompt(%27Enter%20URL%20of%20the%20script%20to%20add%27,%22http://yomama%22)%3Bvar%20oHead%3Ddocument.getElementsByTagName(%27HEAD%27).item(0)%3Bvar%20oScript%3Ddocument.createElement(%22script%22)%3BoScript.type%3D%22text/javascript%22%3BoScript.src%3Dsrc%3BoHead.appendChild(oScript)%3B%7D)()%3B 
