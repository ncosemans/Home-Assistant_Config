  <h4>
    <a href="https://github.com/BeardedTinker/Home-Assistant_Config/actions"><img src="https://img.shields.io/github/workflow/status/BeardedTinker/Home-Assistant_Config/Home%20Assistant%20CI?label=GitHub%20CI&style=plastic"/></a>
    <a href="https://github.com/BeardedTinker/Home-Assistant_Config/stargazers"><img src="https://img.shields.io/github/stars/BeardedTinker/Home-Assistant_Config.svg?style=plasticr"/></a>
    <a href="https://github.com/BeardedTinker/Home-Assistant_Config/commits/master"><img src="https://img.shields.io/github/last-commit/BeardedTinker/Home-Assistant_Config.svg?style=plasticr"/></a>
        <a href="https://github.com/BeardedTinker/Home-Assistant_Config/commits/master"><img src="https://img.shields.io/github/commit-activity/y/BeardedTinker/Home-Assistant_config?style=plastic"/></a>
    <a href="https://discord.gg/HkxDRN6"><img src="https://img.shields.io/discord/675020779955683328?label=Discord%20BeardedHome&logo=discord"/></a><br>


Each commit is verified automaticlly with <a href="https://github.com/BeardedTinker/Home-Assistant_Config/actions">GitHub CI</a> - where it's tested against Latest, Dev and Beta release
  </h4>


# BeardedTinker's Home Assistant configuration

You can find here all of the configuration files from my Home Assistant installation. Updates are pushed whenever there is a change and I do try to work on the system as much as time allows.
I wish to thank all of the Home Assistant community for being inspiration for lot of the things I did here.


## Want to get more info?

You can follow my [YouTube channel](https://YouTube.com/BeardedTinker) for more information and video guides for various stuff that's included here. 

If you want to get in touch, you can always find me on Discord Server - [BeardedHome](https://discord.gg/HkxDRN6) 

Also, if you have time you can try and join me while streaming and there should be at lest one stream each month!


### Hardware

Heart of my smart home is Home Assistant running in Virtual Machine on [Synology DSM920+](https://www.synology.com/en-us/products/DS920+) on DSM version 6.2.4.

Plugged in Synology is Zigbee USB CC2652RB stick from [slae.sh](https://slae.sh/projects/cc2652/) with Zigbee2mqtt firmware from Koenkk.

From other devices I use, here is a list:

##### IKEA DEVICES
  - IKEA TRADFRI Gateway - NOT used anymore
  - IKEA TRADFRI wireless dimmer (ICTC-G-1) - NOT used anymore
  - IKEA TRADFRI remote control (E1524/E1810)
  - IKEA TRADFRI ON/OFF switch (E1743)
  - IKEA TRADFRI control outlet (E1603/E1702)
  - IKEA TRADFRI various bulbs of all sizes and shapes (LED1545G12, LED1623G12, LED1650R5, LED1536G5, LED1649C5, LED1736G9)

##### XIAOMI DEVICES
  - Xiaomi MiJia wireless switch [WXKG01LM](https://www.zigbee2mqtt.io/devices/WXKG01LM.html) - [AliExpress link](https://s.click.aliexpress.com/e/_dW7ZKDA)
  - Xiaomi MiJia temperature & humidity sensor [WSDCGQ01LM](https://www.zigbee2mqtt.io/devices/WSDCGQ01LM.html) - [AliExpress link](https://s.click.aliexpress.com/e/_dUNSKG8)
  - Xiaomi Aqara human body movement and illuminance sensor [RTCGQ11LM](https://www.zigbee2mqtt.io/devices/RTCGQ11LM.html) - [AliExpress link](https://s.click.aliexpress.com/e/_dTTUIzm)
  - Xiaomi Aqara door & window contact sensor [MCCGQ11LM](https://www.zigbee2mqtt.io/devices/MCCGQ11LM.html) - [AliExpress link](https://www.aliexpress.com/item/32967550225.html)
  - Xiaomi Mi/Aqara smart home cube [MFKZQ01LM](https://www.zigbee2mqtt.io/devices/MFKZQ01LM.html) - [AliExpress link](https://s.click.aliexpress.com/e/_dYCODwy)
  - Xiaomi Aqara Vibration sensor [DJT11LM](https://www.zigbee2mqtt.io/devices/DJT11LM.html)- [Aliexpress link](https://s.click.aliexpress.com/e/_dYCODwy)
  - Xiaomi Water sensor [SJCGQ11LM](https://www.zigbee2mqtt.io/devices/SJCGQ11LM.html) - [AliExpress link](https://www.aliexpress.com/item/4001249406915.html)
  - Xiaomi Mosquitto Repellent [ESPHome](https://youtu.be/XMFn8fKhUFA) - [AliExpress link](https://www.aliexpress.com/item/4000195100873.html)

##### SHELLY DEVICES
  - [Shelly EM](https://shelly.cloud/products/shelly-em-smart-home-automation-device/) energy meter with 50A clamp
  - [Shelly Plug S](https://shelly.cloud/products/shelly-plug-s-smart-home-automation-device/) smart Plugs
  - [Shelly Gas CNG sensor](https://shelly.cloud/products/shelly-gas-smart-home-automation-sensor/) 
  - [Shelly Motion sensor](https://shelly.cloud/shelly-motion-smart-home-automation-sensor/)
  - [Shelly Button 2.0](https://shelly.cloud/products/shelly-button-1-smart-home-automation-device/)
  - [Shelly Humidity and Temperature sensor](https://shelly.cloud/products/shelly-humidity-temperature-smart-home-automation-sensor/)
  - [Shelly 1L](https://shelly.cloud/products/shelly-1l-single-wire-smart-home-automation-relay/)
  - Shelly 1
  - Shelly Uno
  - Shelly Door & Window sensor

##### SMART SPEAKERS, DISPLAYS AND SIMILAR
  - Google [Chromcast devices](https://store.google.com/gb/product/chromecast?hl=en-GB)
  - Google [Home Mini](https://store.google.com/gb/product/google_home_mini_first_gen?hl=en-GB)
  - Google [Home Display](https://store.google.com/gb/product/google_nest_hub?hl=en-GB)
  - Lenovo [Smart Clock](https://www.lenovo.com/us/en/smart-clock)
  - LG webOS TV
  - Mi TV stick

##### HEATING
  - tado° [Smart Thermostat](https://www.tado.com/hr/)
  - tado° [Smart Radiator Thermostat](https://www.tado.com/us/products/smart-radiator-valve)
  
##### CAMERAS
  - Reolink RLC-410-5MP PoE camera
  - various DLink PoE IP cameras 
  
##### OTHER DEVICES
  - Tile [Mate 2020](https://www.thetileapp.com/en-us/store/tiles/mate)
  - Elgato [Key Light Air](https://www.elgato.com/en/gaming/key-light-air)
  - [Roborock S5 max](https://us.roborock.com/pages/roborock-s5-max)
  - [QuinLED-Dig-Uno](https://quinled.info/2018/09/15/quinled-dig-uno/) for controlling addressable LED strips
  - [ioios.io](https://ioios.io/) Pithy Display and Pithy Pixel 
  - [Nuki 2.0 Combo](https://nuki.io/en/smart-lock/) Smart Door lock with bridge & [Nuki Opener](https://nuki.io/en/opener/)

### Containers and add-ons

As I'm running this on Synology, I have mix of Docker containers and Home Assistant add-ons. Here is a list:

Add-ons:
  - Assistant Relay - [link](https://github.com/Apipa169/Assistant-Relay-for-Hassio) - TO BE REMOVED
  - ESPHome - [link](https://esphome.io/) 
  - Samba share - [link](https://github.com/home-assistant/hassio-addons/tree/master/samba)
  - Samba Backup - [link](https://github.com/thomasmauerer/hassio-addons)
  - Terminal & SSH - [link](https://github.com/home-assistant/hassio-addons/tree/master/ssh)
  - Visual Studio Code - [link](https://github.com/hassio-addons/addon-vscode)
  - Zigbee2MQTT -[link](https://github.com/zigbee2mqtt/hassio-zigbee2mqtt/tree/master/zigbee2mqtt)

Containers:
  - VaultWarden
  - Facebox
  - Grafana
  - InfluxDB
  - MQTT
  - Node-RED
  - Portainer
  - Prometheus
  - Smokeping
  - Storagenode
  - Storj Exporter

### Integrations

There are too many integrations to list them all, but some of the main ones are:
  - Telegram for notifications and control
  - Zigbee2MQTT for controlling (and now also updating) my Zigbee devices
  - Google for integration with Google Assistant and various Home devices
  - Synology for Surveillence station and Synology system statistics and info
  - HACS - Home Assistant Community Store - for even more custom components and plugins
  - influxDB - storing data generated by Home Assistant
  - OctoPrint - to see what my Ender 3 Pro 3D printer is doing
etc...

Following is a list of active Integrations that are visible at Configuration->Integration page:
  - AccuWeather
   - AirVisual
  - Blitzortung (HACS)
  - Certificate Expiry
  - COVID-19
  - Elgato Key Light
  - EPSHome
  - GDACS
  - Google Cast
  - HACS
  - Home Assistant Supervisor
  - Internet Printing Protocol
  - Kraken
  - Luftdaten
  - Mikrotik
  - Minecraft Server
  - Mobile App
  - MQTT
  - Network UPS Tool
  - Nuki
  - ONVIF
  - OpenUV
  - Reolink
  - Shelly
  - Shopping List
  - SpaceX
  - SpeedTest
  - Synology DSM
  - Tado
  - Tile
  - WLED on [QuinLED Dig-Uno](https://quinled.info/2018/09/15/quinled-dig-uno/) boards
  - Xiaomi Miio


## Folder structure and files

Insipred by [Franck](https://github.com/frenck/home-assistant-config) I've broken my configuration in various files.

It looks overwhelming at first, but when you get the hang of it, this structure is much easier to maintain and find something. Also disabeling parts of the integrations is just a rename away :)

## Counters

Up-to-date count of various things in Home Assistant 

| Type                 | Count |
| -------------------- |:-----:|
| Alerts               |     4 |
| Automations          |   159 |
| Binary sensors       |   214 |
| Cameras              |    11 |
| Climates             |     4 |
| Counters             |     2 |
| Device trackers      |    56 |
| Entities             |  1770 |
| Groups               |    17 |
| Image Processing     |     1 |
| Input Boolean        |    13 |
| Input Date/Time      |    23 |
| Input Number         |    11 |
| Input Select         |    10 |
| Input Text           |     4 |
| Lights               |    39 |
| Lines of code (YAML) | 19496 |
| Locks                |     3 |
| Media players        |    41 |
| Persons              |     6 |
| Plants               |     7 |
| Rest commands        |    13 |
| Scripts              |    17 |
| Sensors              |  1024 |
| Switches             |    66 |
| Timers               |     4 |
| Utility Meters       |     5 |
| Vacuums              |     1 |
| Weather              |     3 |


### Missing files

Due to privacy, security,... some files are not included as well as some folders.

Here is a list of them sorted:
#### Missing folders
  - www/community

#### Missing files
Most of the missing files now have sample version. This is edited version with "fake" information, so you are able to reuse code.

  - ip_bans.yaml - could contain IP addresses  - added SAMPLE
  - secrets.yaml - contains credentials and some private infos - added SAMPLE
  - known_devices.yaml - contains indentifiers  - added SAMPLE
  - customize.yaml - contains private information - added SAMPLE
  - facebox-*.yaml - contains information for face recognition - added SAMPLE
  - google_calendars.yaml - contains private information - added SAMPLE
  - telegram_gps_response_andrej.yaml - contains identifiers - added SAMPLE
  - telegram_gps_response_luka.yaml - contains identifiers
  - telegram_gps_response_mirta.yaml - contains identifiers

Also missing are certificates, json files, cookies,...
