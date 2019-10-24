## This is a sample app that allows you to spoof GPS location

### Requirements:

- Mac OS
- Xcode (https://apps.apple.com/au/app/xcode/id497799835?mt=12)

### How to run apps in your device:

https://www.twilio.com/blog/2018/07/how-to-test-your-ios-application-on-a-real-device.html

### How to use:

1. Download the project in your machine
2. Open the project
3. Select GPSLocation.gpx file (https://github.com/vitorll/GPSFuelApp/blob/master/GPSFuelApp/GPSLocation.gpx)	
	- ![location_file_image](GPSFuelApp/location_file_image.png)
4. Enter the desired GPS coordinates
5. Select your device as target
6. Change the bundle identifier for the project (needs to be unique eg. com.yourcoolname.GPSFuelApp)
	- ![bundle_identifier](GPSFuelApp/bundle_identifier.png)
7. Run the project
8. Enable location simulation	
	- ![location_feature_image](GPSFuelApp/location_feature_image.png)

Now your iPhone will use the same location as defined in the GPSLocation.gpx file. 

You can now change to any maps app to check out if it's working

That's it
