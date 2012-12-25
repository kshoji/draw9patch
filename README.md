draw9patch
==========

Customized draw9patch (Android resource image editor)

- Drawing the patch with the mouse draging.
- No resetting controls when an another image has been loaded.
- Same patch will be applied when the same size image has loaded.
- Don't display save dialog if there's no ".9.png" file in the source image's directory.

Installation
============

- Open the `$ANDROID_HOME/tools/lib` directory.
- Backup the original `draw9patch.jar` file.
- Download the file [draw9patch.jar](https://github.com/kshoji/draw9patch/blob/master/draw9patch.jar) from this repository.
- Place the new draw9patch.jar file to `$ANDROID_HOME/tools/lib`.

Build
=====

- Import this project into Eclipse workspace, and build it.
- Select the source file `src/com.android.draw9patch/Application.java` and run it. Then quit the application.
- Select the project, and export this project as 'Runnable JAR file'. Set 'Launch configuration:' to `Application - draw9patch`.

License
=======
Same as the original. [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
