ArcGIS Runtime API Toolkit
==========================

Current Release: 10.2.6 Final,  June 2015

This project contains QML source code for controls and utilities you can use with the [ArcGIS Runtime SDK for Qt](http://developers.arcgis.com/qt). There are QML examples in this repo that demonstrate the use of these controls and how they can be used as reusable building blocks for your QML-based ArcGIS applications.

## Features
- UserCredentialsDialog - a dialog that takes in a username and password. It can be connected with a UserCredentials instance and a Portal instance to sign into Portal for ArcGIS or ArcGIS Online. The dialog is customizable, as the top banner and several labels can be changed.
- MapNavigation Toolbar - a toolbar control with 4 buttons: 
    -   Show your location on the map
    -   Zoom in
    -   Zoom out
    -   Home (Back to full extent)
- NorthArrow Control - a compass that points toward true north and the map angle in degrees as the map rotates.
- Overview Map Control - an overview map control.
- PortalItemsView Control - A control that provides a scrollable list of Portal items based on a Portal URL and a query for specific portal items.
- PortaItems Dialog - A dialog containing a list of items from a Portal.
- StyleTemplate Control - a way to style your toolbars and buttons the way you want.
- SearchBox Control - allows you to search the map content for addresses and places.

## Instructions 

1. Fork and then clone the repo or download the `.zip` file.
2. The Toolkit requires the ArcGIS Runtime SDK for Qt.  Confirm that your system meets the requirements for using the ArcGIS Runtime SDK for Qt (http://developers.arcgis.com/qt/qml/guide/arcgis-runtime-sdk-for-qt-system-requirements.htm).  
3. From Qt Creator, go to __File->Open File or Project...__ on the toolbar, browse for the `.qml` files from your cloned repo, and open them. 
4. Once these have been added to your Qt Creator, double-click `Example.qml` to open it in the editor. 
5. To run the QML Example app, on the toolbar go to __Tools->External->ArcGIS Runtime->ArcGIS Runtime Sample App__. The QML Example app with open, and you can use the pulldown to select each individual example program that demonstrates a specific control.
6. Browse the QML code to see how to utilize the control

## Resources

* [ArcGIS Runtime SDK for Qt](https://developers.arcgis.com/qt/)
* [Qt and QML](http://www.qt.io/)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Anyone and everyone is welcome to contribute.

## Licensing
Copyright 2014 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](license.txt) file.


[](Esri Tags: ArcGIS Runtime SDK Qt QML)
[](Esri Language: Qt)

