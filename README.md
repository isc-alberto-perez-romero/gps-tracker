# GPS-Tracker

GPS tracker solution proposal, by Alberto Pérez Romero (ing_aperezr@yahoo.com).


Planned and developed as a demonstration of my development abilities using:

  - Server-side JavaScript (using Node.js),
  - Server-side TypeScript,
  - Server-side Java,
  - MongoDB,
  - MariaDB/MySQL,
  - Client-side Unity+C#, and
  - Client-side Java.

  
(Future updates featuring Java for Android, Swift for iOS, C++ for Windows, and
AngularJS are intended).



## Abstract
 
The development contained within these directories intends to provide a 
solution for inventoring and monitoring several objects with built-in 
GPS-tracking devices, highlighting those for which signals have not been
received for longer than 5 minutes.



## Scenario

This solution will allow several users to sign into the system.

ADMIN-type users will be able to add other users and GPS-trackable objects.
OPERATOR-type users will only be able to add GPS-trackable objects.
Both types of users will be able to monitor the added objects.

Added objects will communicate, via several client implementations, with the
server. Upon connecting for the first time, or after having been deactivated,
they will send their current location once in a minute (this parameter should
be configurable). 
 
The dashboard will display all active objects, highlighting those for which
information has not been received for longer than 5 minutes.



## Version control information

Version control will be performed via Git.