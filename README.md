# About this demo app
This Splunk app is used as a step by step tutorial for demonstrating some Splunk features about knowledge objects.

This git repo contains 11 labels from 1.0 to 1.10 which progressively enhance the Splunk app and show you the usage of different knowledge objects in Splunk.

# How to use it
## Use it without running the Splunk app
You can simply clone the git repository and check out each label in the repository for changes.

* git clone this repo
* git checkout tags/1.0, take a look at Changelog.md for changes
* git checkout tags/1.1, take a look at Changelog.md for changes
* ...
* git checkout tags/1.9, take a look at Changelog.md for changes
* git checkout tags/1.10, take a look at Changelog.md for changes

## Use it by running the Splunk app
Vagrant is used for setting up a Splunk app automatically, and you can clone this git repository and use Vagrant to automatically set up the environment for you and you can see the live demo by yourself.

* Install Vagrant
* git clone this repo
* Download splunk Linux edition and name it as 'splunk-6-linux-2.6-x86_64.rpm' and put it under 'splunk/assets' folder
* git checkout tags/1.0
* vagrant up
* Splunk web is available via http://192.168.33.3:8000
* Check out Changelog.md and take a look at splunk web for the changes
* git checkout tags/1.1
* vagrant destroy; vagrant up
* Check out splunk web for the changes
* git checkout tags/1.2
* vagrant provision
* Check out splunk web for the changes
* ...
* git checkout tags/1.10
* vagrant provision
* Check out splunk web for the changes

# NBA stats download
http://basketballvalue.com/downloads.php

Putback reverse dunk shot video, http://www.youtube.com/watch?v=4g2jNyTACfk

# Some related Splunk documentations
http://docs.splunk.com/Splexicon:Knowledgeobject

http://docs.splunk.com/Documentation/Splunk/6.1.2/Knowledge/AboutSplunkregularexpressions

http://docs.splunk.com/Documentation/Splunk/6.1.2/SearchReference/Commonevalfunctions

http://docs.splunk.com/Documentation/Splunk/6.1.2/SearchReference/Abstract

http://docs.splunk.com/Documentation/Splunk/6.1.2/Knowledge/Createandmaintainsearch-timefieldextractionsthroughconfigurationfiles#Create_advanced_search-time_field_extractions_with_field_transforms

# Regular expression
http://regex101.com, online regex tester, use pcre (perl compatible regular expression)

http://www.php.net/manual/en/book.pcre.php