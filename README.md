Memo for myself
===================================

It didn't build successfully for the first try because of the version of gradle and plugin. 
I did research a bit and according to this website (https://stackoverflow.com/questions/57755725/how-to-fix-error-could-not-find-method-google-for-arguments-on-repository), I had to update the distribution URL and classpath in "build.gradle". I changed the distribution URL to 6.5-bin.zip and classpath to "4.1.1" as the website provided. And everything worked successfully.
 
Quake Report App
===================================

This app displays a list of recent earthquakes in the world
from the U.S. Geological Survey (USGS) organization.

Used in a Udacity course in the Beginning Android Nanodegree.

More info on the USGS Earthquake API available at:
https://earthquake.usgs.gov/fdsnws/event/1/

Pre-requisites
--------------

- Android SDK v23
- Android Build Tools v23.0.2
- Android Support Repository v23.3.0

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

Support
-------

- Google+ Community: https://plus.google.com/communities/105153134372062985968
- Stack Overflow: http://stackoverflow.com/questions/tagged/android

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2016 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
