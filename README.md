## Galaxy Nexus, Android 4.3 & Bluetooth Low Energy

Add [Bluetooth Low Energy](http://www.bluetooth.com/Pages/Low-Energy.aspx) (BLE) support to the Galaxy Nexus with Android 4.3. This mod works for every ROM (stock or custom) and uses the [official BLE API](http://developer.android.com/guide/topics/connectivity/bluetooth-le.html) of Android 4.3.

The Galaxy Nexus has a Samsung `SWB-B42 BT 4.0 Dual Band` Bluetooth chip. This mod add BLE software support. You need a root access to flash your device with new files/libraries to bring BLE support.

__Warning: after flashing your device, you will not be any more able to get system (Android) updates from Google.__

### Requirements
To use this mod, you will need :

* A __Galaxy Nexus phone__ (tuna) with __root access__.
* An official or custom __Android 4.3 ROM__.

### Tests
This mod has been tested on a rooted Galaxy Nexus "maguro" (GSM/HSPA+) phone `tuna, yakju` with the official Android 4.3 ROM `build JWR66V`.<br>
The BLE communication works great between the Galaxy Nexus and an nRF Development Kit from Nordic Semiconductor.

__Android BLE applications__

* Simple app which checks for BT 4.0 BLE support on an Android device<br>
https://github.com/tadejkolino/BLECheck

* BLEScanner<br>
https://android-ble.googlecode.com/hg/BLEScanner/Android-App/BLEScanner-0.1.apk

* Google Bluetooth LE sample<br>
http://developer.android.com/tools/samples/index.html

### Links

* Samsung Galaxy Nexus Teardown: http://www.ifixit.com/Teardown/Samsung+Galaxy+Nexus+Teardown/7182/2#s30574
* Bluetooth Low Energy: http://en.wikipedia.org/wiki/Bluetooth_low_energy
* DevBytes: Bluetooth Low Energy API in Android 4.3: http://youtu.be/vUbFB1Qypg8

***

>Thanks to [manuelnaranjo](https://github.com/manuelnaranjo), files are based on his [commit](https://github.com/manuelnaranjo/android_device_asus_grouper/commit/665584952478441e3fe8e70f32d2f2ee11f6ac27) and to [madd0g](http://forum.xda-developers.com/member.php?u=2562042) for his post on [xda-developers.com](http://forum.xda-developers.com/showthread.php?t=2387107).