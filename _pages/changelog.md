---
layout: page
title: What's New
include_in_header: true
---

# Changelog

## `Latest`


### **Version 2.2.3 (2020/2/5)**

#### Feature

- add BLE node
- add node-red-contrib-image-output@0.5.2
- add camera node sample
- change the return value when taking a photo

#### Update Nodes

- node-red-node-email@1.7.4

#### Breaking Change

msg.payload has been modified from array to string in the method to take a picture of the camera node.

#### Note

When using a BLE node, allow the permissions of

- android.permission.BLUETOOTH 
- android.permission.BLUETOOTH_ADMIN

----

### **Version 2.0.1 (2020/1/11)**

#### Bugfix

- fixed that data cannot be overwritten by msg.payload on serial node

#### Update Nodes

- node-red-contrib-cast@0.2.13
- node-red-node-email@1.7.4

### **Version 2.0.0 (2020/1/2)**

#### New Node

- sqlite node

### **Version 1.9.7 (2019/12/15)**

#### New Node

- node-red-contrib-ui-svg@1.2.2

#### Update Packages

- node-red-dashboard@2.19.2
- node-red-node-email@1.7.3
- node-red-node-feedparser@0.1.15
- node-red-node-twitter@1.1.6

### **Version 1.9.6 (2019/12/1)**

#### What's New

Update Packages

- node-red-dashboard@2.19.0
- node-red-contrib-telegrambot@7.0.0
- node-red-contrib-cast@0.2.12

### **Version 1.9.5 (2019/11/23)**

#### What's New

- update node-red@1.0.3
- update node-red-node-email@1.7.2

### **Version 1.9.4 (2019/11/9)**

#### What's New

- update serial node
- update pacakges
    - node-red-contrib-telegrambot@6.0.0
    - node-red-node-base64@0.2.0

### **Version 1.9.1 (2019/10/19)**

#### What's New

- Updated the vulnerable library to improve security
- update packages
    - Node-RED@1.0.2
    - node-red-dashboard@2.17.1

### **Version 1.9.0 (2019/10/05)**

#### What's New

- update packages
    - Node-RED@1.0.1
    - node-red-dashboard@2.17.0

### **Version 1.8.1**

#### What's New

- add startActivityNode
- update Node-RED@0.20.8
- update node-red-contrib-telegrambot@5.5.2
- update node-red-dashboard@2.16.2

### **Version 1.7.1**

#### What's New

- add the serial USB node
- add the volume node that allows volume control

### **Version 1.6.1**

#### What's New

- add the camera node

#### Bug Fixes

- Fixed background notification message

### **Version 1.5.0**

#### What's New

- update Node-RED@0.20.7
- update node-red-dashboard@2.15.5
- update node-red-contrib-cast@0.2.8

### **Version 1.4.12**

#### Bug Fixes

- Fixed AutoStart

### **Version 1.4.11**

#### What's New

- update Node-RED@0.20.6
- update node-red-dashboard@2.15.4
- add keepAwake switch

### **Version 1.4.6**

#### What's New

- update some modules

### **Version 1.4.5**

#### What's New

- add node-red-contrib-cast

### **Version 1.4.3**

#### What's New

- add node-red-node-dropbox

### **Version 1.4.2**

#### What's New

- add node-red-contrib-telegrambot

### **Version 1.4.1**

- minor bug fixes

### **Version 1.4.0**

#### What's New

- add dBNode
- add AutoStart Switch

### **Version 1.4.0**

#### What's New

- add dBNode
- add AutoStart Switch

### **Version 1.3.9**

#### What's New

- change support api level from 21+ to 22+

### **Version 1.3.8**

#### What's New

- update icon
- update ip address when app is displayed

### **Version 1.3.7**

#### What's New

- optimized background behavior (do not terminate the app with the back button)
- add App Shortcuts menu ( android 7.1 or later)
  - show Dashboard
  - pinned Dashboard（Android 8.0 or later)

### **Version 1.3.5**

- minor bug fixes

### **Version 1.3.4**

#### What's New

- add Magnetic Sensor Node

### **Version 1.3.3**

#### What's New

- add Gyroscope Sensor Node
- update ui

### **Version 1.3.2**

#### What's New

- update NodeRED@0.20.5
- update nodejs@10.13.0

### **Version 1.3.1**

#### What's New

- add the ability to update NodeRED's flows by updating local flows.json from the app.

### **Version 1.3.0**

#### What's New

- add dashboard access button

### **Version 1.2.11**

#### Bug Fixes

- fix link connection

### **Version 1.2.10**

#### What's New

- update node icon

#### Bug Fixes

- fix speech synthesis node

### **Version 1.2.9**

#### What's New

- add node-red-contrib-mqtt-broker
- add node-red-node-base64

### **Version 1.2.8**

#### What's New

- Modified the display part of the IP address.
- With this modification, it also supports IP address display when using Wifi Hotspot.

### **Version 1.2.7**

#### What's New

- add proximity node
- change node name

### **Version 1.2.6**

#### What's New

- add vibrate node
- add dialogs node（alert, confirm, prompt, beep)
- supports URL scheme (redmobile://)

### **Version 1.2.5**

#### What's New

- add InAppBrower node

### **Version 1.2.4**

#### What's New

- update NodeRED@0.20.3
- add voice recognition node
- add speech synthesis node
- remove tail node

### **Version 1.2.3**

#### What's New

- add geolocation node
- add battery status node

#### Bug Fixes

- fixed an internal error caused by the contents of the port
- fixed an issue where could enter a value less than zero in the port number

### **Version 1.2.2**

#### What's New

- add motion node
- add light node
- add compass node

### **Version 1.1.3**

#### What's New

- update Node-RED@0.20.2

### **Version 1.1.2**

#### What's New

- add loading animation

### **Version 1.1.1**

#### What's New

- add port check function
- speed ​​up display of server url

### **Version 1.1.0**

#### What's New

- update Node-RED@0.20.0
