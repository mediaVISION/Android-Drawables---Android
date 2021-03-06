Android Resource Viewer
========================
Description
-----------
This application will list all public and private Android resources (i.e. resources located under 'android.R.*' and under 'com.android.internal.R.*') for the current device.

If the resource is a drawable or a colour the background colour of the list can be changed to see how it looks next to a different colour.

* This application used to be called Android Drawables.
* This is not a drawing app.
* Probably only useful to developers :)
* No ads.

WARNING: Internal resources (anything under 'com.android._internal_.R') are not guaranteed to be in all devices/android versions.
Do not reference them directly in your application or it will crash on untested device configurations.

Changelog
-----------
* v0.0.1: First public release.
* v0.0.2: Changed icon, minor bugfixes, added copy functionality.
* v0.0.3: Code cleanup, now compiles against v14.
* v0.0.4: Added other resource types.
* v0.0.5: Changed application name, resource types are now automatically enumerated.
* v0.0.6: Resource list in now alphabetically sorted.

Permission Explanation
-----------
* No permissions needed.

Build Instructions
--------------
You will need the following libraries to build this project:

* My fork of NewQuickAction3D which can be found here: [https://github.com/alt236/NewQuickAction3D](). It is an android library project, which means you might need to edit the library reference in this project's Android preferences.
* ActionbarSherlock v4+: [https://github.com/JakeWharton/ActionBarSherlock]()

Acknowledgments
-----------
Original icon by OCAL ([http://www.clker.com/clipart-style-paintbrush.html]()).
All logos are the property of their respective owners

License
-----------
Licensed under the Apache License 2.0: [http://www.apache.org/licenses/LICENSE-2.0.txt]()
	
Links
-----------
* Market link: [https://market.android.com/details?id=aws.apps.androidDrawables]()
* Webpage: [http://aschillings.co.uk/html/android_drawables.html]()
* Github: [https://github.com/alt236/Android-Drawables---Android]()