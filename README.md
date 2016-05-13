Slimserver plugin for easy virtual libraries
============================================

This plugin provides an easy mechanism for defining library views for the
Logitech Media Server.

Requirements
------------

This plugin requires Logitech Media Server v7.9.0 or greater.

Installation
------------

Add the following repository to your Logitech Media Server:

http://software.gently.org.uk/slim-plugins/repo.xml

The 'Easy Virtual Libraries' plugin should now be available for installation.

Usage
-----

In order to use the Easy Virtual Library plugin, first you should define the names of the virtual libary views you wish to create. This is done by entering the list of library view names into the plugin's settings page, separating each name with a semi-colon.

Once the names of the library views have been defined, albums can be added to a library view by creating a file named:

'easy-virtual-library-libraryviewname' (note that this file name does not have any extension)

in the directory containing the album's media.

e.g. to add an album to the library 'audiobooks', create a file called 

'easy-virtual-library-audiobooks' 

in the album's directory.

Library views wiil be updated the next time a scan is triggered, or if changes are made to the list of library view names on the plugin's settings page.


