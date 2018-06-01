Pushbullet app and device code for Hubitat Elevation
* Originally written for SmartThings by Eric Roberts
* Adapted to Hubitat Elevation by Brian S. Lowrance (Rayzurbock)

PushBulletConnect.groovy is the App Code
PushBullet.groovy is the Driver Code
Both must be installed.

1. Install both the App and Driver code into your Hubitat.
2. Login to https://www.pushbullet.com  (or create an account and setup your device(s))
3. Click on your profile picture (top right) > My Account
4. Click Create Access Token
5. Copy the code shown  (Save it somewhere for future use, you'll need it to add additional push bullet devices!)
6. Go to your Hubitat portal
7. Click Apps > Load New App
8. Scroll down and select Pushbullet Connect and select it
9. Past in your API Key (Access Token)
10. Select the device you wish to connect with
11. In Hubitat go to Device and find your device by the name it has in Hubitat
12. Click the test button
13. Check your device for your notification
14. Configure any app that supports "Speech Synthesis" to "Speak" your notification

* Push() functions have been disabled in this app from the original as Push Notifications are really not supported in Hubitat yet.  Speak() does the same function, use that.
