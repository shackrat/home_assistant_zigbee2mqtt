This code works by scanning for devices with unique ID strings that contain "zigbee2mqtt_0x" which is the standard prefix Z2M users, it then filters by devices where the parent_device_id matches the coordinator's ID. 
It then monitors the first entity of each device where the matches the Zigbee2MQTT device id, and counts all values that are not unknown.

To use this template, first create a Template Helper in the UI and past the code in below for the template. 
You will need change "7e32275795a7f713992a0544d7226584" which is the ID of my channel 11 coordinator to match the device ID of your coordinator. 
You can easily grab the device ID from the URL of the device details page for your coordinator.

Good Luck!
