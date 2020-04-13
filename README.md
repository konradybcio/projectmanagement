Working
-------
* Actors: Manual brightness
* Cellular: Carrier info, signal strength
* Cellular: SMS in, out
* GPU: Boot into UI
* Misc: Battery percentage
* Misc: Online charging
* Misc: Shutdown / Reboot
* Network: WiFi
* Network: Flight mode
* Sensors: Touchscreen
* Sound: Loudspeaker
* USB: RNDIS access
* Sound: Volume control
* Network: Bluetooth
* Actors: Notification LED
* Actors: Vibration
* Cellular: Data connection
* Cellular: Incoming, outgoing calls
* Network: Hotspot

* GPU: Video acceleration

Working with additional steps
-----------------------------

Not working
-----------
* Misc: Offline charging (seems to work but device reboots after a few seconds)
* (Network: NFC - disabled atm due to no middleware)

* Actors: Torchlight
* Camera: Flashlight
* Camera: Photo
* Camera: Video
* Cellular: PIN unlock
* Cellular: Change audio routings
* Cellular: Voice in calls
* Misc: Anbox patches applied to kernel
* Misc: Recovery image
* Misc: Reset to factory defaults
* USB: MTP access (use SCP, people! :P)
* Sound: Earphones
* Sound: Microphone

This device doesn't use sensors.qcom and therefore all sensors are borked

* Sensors: Automatic brightness
* Sensors: GPS
* Sensors: Proximity
* Sensors: Rotation

Untested
-----------------------------
* USB: External monitor - only for devices that support it
* Cellular: MMS in, out
* Endurance: Battery lifetime > 24h from 100%
* Endurance: No reboot needed for 1 week

Hardware-unsupported features
-----------------------------
* (Sensors: Fingerprint reader - disabled atm due to no middleware)
* Misc: Wireless charging - only for devices that support it
