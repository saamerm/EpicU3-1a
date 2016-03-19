# EpicU3-1a
___________________________
Stanford developing for ios7
============================
Class I-Class logistics and overview
++++++++++++++++++++++++++++++++
// 5pm 3/19/2016

Object Oriented Terms:-
1) Class (description/template for an object)
2) Instance (manifestation of a class)
3) Message (sent to object to make it act)
4) Method (code invoked by a message)
5) Instance Variable (object-specific storage
6) Superclass/Sub Class (inheritance)


1) Cocoa Touch -UI layer - Alerts, Slides, Mapskit, Localisation (publish in all countries)
2) Media - ipods with a phone on them. Video, video editing, pictures to display, audio
3) Core Service - Things that make the language more powerful-to access the file system, GPS, arrays, multithreading, dictionaries
4) Core OS - CLose to the hardware. Unix operating system kernel-file systems, sockets, power management, key chain access, bonjour

Platform Components
1) Tools - Xcode 5
2) Language -Objective C
3) Frameworks (libraries in iOS)- Two main ones, Foundation (arrays functions) & UIKit (buttons sliders), CoreData, CoreMotion (Gyro accelerometer)
4) Design Strategies -MVC Model View Controller Strategy for how to organize all the classes in the application

MVC-
1) Model- Completely independent of how the UI (view) works. Songs database
2) Controller-Control HOW the model is presented
3) View- Things we are going to use in the UI
Note-Controller cant talk to both Model & View. Controller has full uncontrolled access from Controller to the Model. Controller uses the minions in the view ot do whatever it wants

View Protocols-
1) Action/Target - Blind messages sent to controller
2) Delegate - More complicated-Will, should, did. Eg. scroll-Is it allowed?
