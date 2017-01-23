
# Home Assistant Configuration
[Home Assistant](https://home-assistant.io/) on a RPi3.

## Changelog:

* v0.1 - Base Configuration and File Structure
* v0.2 - Sensor Data
* v0.3 - Added Components (Wink, Hue, Harmony, Plex)
* v0.4 - Groups/Tabs, Cleanup
* v0.5 - Speedtest, Synology, Sonarr, NZBGet and Hubs
* v0.6 - Cleanup, Speedtest, Fix Installed Version and more efficient Release detection
* v0.7 - Fix for Synology, Added Nest Protects
* v0.8 - Presence detection added, Universal Media Player and Log Tuning and Added to README


## Issues
* spaces Paul, not tabs...
*

## Layout
- The *Home* group is the default_view and shows relevant information I want at first glance.
- The *Local* group is a local dashboard with the most useful information about Calgary
- The *Security* group shows Smoke & Carbon Monoxide Detection, Door and Windows Status, etc (locks and gate to come)
- The *Media* group is for Home Entertainment, etc.
- The *System* group is for Home Infrastructure related items and status. 

## Screenshots
![Home](https://www.dropbox.com/s/sa5kjopf8k28dre/home.png?raw=1)
![Local](https://www.dropbox.com/s/0q1zrq6zsszji5d/local.png?raw=1)
![Security](https://www.dropbox.com/s/2pjkwkxaqbre601/security.png?raw=1)
![Media](https://www.dropbox.com/s/56xao6x4h7kh9sa/media.png?raw=1)
![System](https://www.dropbox.com/s/xaw8fmph61ky3xx/system.png?raw=1)


## Acknowledgments
* Hat tip to [jtscott] (https://github.com/jtscott/hass-config)
* All the [Home Assistant examples](https://home-assistant.io/cookbook/) and contributors.

## Devices
- RPi3 on Raspian Jessie
- Nest Protect (2)
- Xiaomi Mi Box
- Unifi Wireless
- ecobee3 (6 sensors)
- Wink 2 Hub
- Philips Hue Lights
- Philips Hue Bridge
- Harmony Companion Hub
- Plex Media Server
- Synology NAS
- Chamerlain MyQ Garage Door

## Automations
- Nothing yet