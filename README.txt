The following steps need to be done to create a jmdns.jar that works with
android:

** run: mkdir unjar
** run: cd unjar
** run: jar xf ../jmdns.jar
** run: jar cfm ../jmdns.jar META-INF/MANIFEST.MF javax/
**
** copy jmdns.jar into clementine-remote-android/libs

Source: http://home.heeere.com/tech-androidjmdns.html