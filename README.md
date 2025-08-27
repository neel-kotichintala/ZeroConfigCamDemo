# ZeroConfigCamDemo
Demo of the Zero Configuration Project (In progress...)

# Web App
## Dashboard
#### This is where the live camera feed will be displayed from each connected camera
1. Camera cards with camera stream
2. Each card contains a unique ID as the default name of the camera
3. Settings within each card to change resolution and quality
   
![alt text](https://github.com/neel-kotichintala/ZeroConfigCamDemo/raw/main/demo/dashboard.png)

## Setup
#### This is where the user can add their cameras that they want to stream
1. Enter WiFi credentials (SSID, Password)
2. Click generate QR code
3. Scan QR Code with camera
4. Once scanned, the camera will connect to your WiFi and connect to the main server via Web Socket to start streaming live video

![alt text](https://github.com/neel-kotichintala/ZeroConfigCamDemo/raw/main/demo/setup.png)

## Settings
#### This is a simple settings tab with a few controls over the user's account
1. Apperance: Light or Dark Mode
2. Network: Completely Optional Network Configurations
3. Notifications: Controls over which notifications the user wants

![alt text](https://github.com/neel-kotichintala/ZeroConfigCamDemo/raw/main/demo/settings.png)

## Camera Views
#### These options on the top right of the camera dashboard allow the user dynamically switch between different camera views
1. Grid View: The connected camera streams will be shown in a grid format which allows the user to see all of the cameras at the same time
2. List View: The connected camera streams will be in full screen mode but the user needs to scroll to see other camera streams
3. Full View: The connected cameras streams will be in the maximum size on your screen depending on the browser size, and the user can click the arrows on either side to view other camera streams

![alt text](https://github.com/neel-kotichintala/ZeroConfigCamDemo/raw/main/demo/camera_view.png)

# Cameras
