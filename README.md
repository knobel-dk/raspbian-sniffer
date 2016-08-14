# raspbian-sniffer
This script will turn your Raspberry Pi 3 into a wireless access point that logs all requests to it.

## The story behind this script:
iOS and Android devices are regularly scanning for available wireless access points. The devices use it to match GPS and cell tower location data together with WiFi networks. Apple has been in [trouble]
(http://www.theverge.com/2013/11/27/5153954/iphone-location-tracking-lawsuit-against-apple-is-dismissed) and so has [Google](http://arstechnica.com/tech-policy/2011/04/google-faces-50-million-lawsuit-over-android-location-tracking/).

Your wireless router is most likely being scanned by dozens of devices every day. Image if you could log that. Here is some insights you can reach with such a log at your disposal:
* Authorities can plan public transportation based on the amount of commuters
* Store owners can see the number of returning customers by looking at the MAC address
* [list more]

## How to use
Tested on Raspbian Jessie 4.4
