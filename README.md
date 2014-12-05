adt-leanback-support
====================

Eclipse ADT compatible versions of the android leanback libraries and support libraries.

To build:

1. You need to install Android L to your maven repository using the maven-android-sdk-deployer.
2. Build the this project by typing: mvn clean install

To import these projects into eclipse, make sure you have m2e 1.4 or higher and m2e-android
extension installed.  Then import the projects as existing maven projects.

All items are generated as APKLibs, the support-v4 project is available as apklib or jar.

This library is based on the Android 5.0 21.0.2 code and will change when google releases the
latest source.  It should be enough though to let you do Android TV development with ADT for Eclipse.

