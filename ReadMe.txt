DockBrowser
===========

ABOUT:

This sample demonstrates how to use NSNetServices to take advantage of Bonjour service discovery and name resolution on Mac OS X.


How it Works

This sample creates a small application that can be used to browse for services by using its Dock menu.  To see the application's Dock menu, simply control+click or click+hold on its Dock icon.  Selecting one of the discovered services will automatically connect you to the service.  This sample is hard wired to browse for services of type "_afpovertcp._tcp." (AppleShare servers) or services of type "_http._tcp." (Web servers) and you can toggle between the two by using the application's Preferences window.

Browsing for "_http._tcp." is a good way of locating Bonjour enabled hardware devices, because many of these devices will contain a built-in web server used for configuring the device.

This sample also allows you to advertise a fake instance of "_afpovertcp._tcp." or "_http._tcp." so that anyone browsing for these service types can locate you.  You can toggle this setting by going to the application's Preferences.


===========================================================================
BUILD REQUIREMENTS

Xcode 3.2, Mac OS X 10.6 Snow Leopard or later.

===========================================================================
RUNTIME REQUIREMENTS

Mac OS X 10.6 Snow Leopard or later.

===========================================================================
CHANGES FROM PREVIOUS VERSIONS

Version 1.2
- Project rewritten in Cocoa.
- Project updated for Xcode 4.
Version 1.1
- Updated to Native Xcode target.
Version 1.0
- Initial Version

===========================================================================
Copyright (C) 2003-2011 Apple Inc. All rights reserved.
