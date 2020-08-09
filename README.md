# Table of Contents
- [Resources](#resources)
- [Notes](#notes)

----

## Resources
- good setup instructions 
  - https://medium.com/macoclock/setting-up-mac-for-opencv-java-development-with-intellij-idea-fd2153eb634f
  - see [notes](#notes) section for barriers
- openCV docs
  - https://opencv-java-tutorials.readthedocs.io/en/latest/index.html
- openCV Additional Modules
  - https://code.amazon.com/packages/Opencv/blobs/Opencv-4.0.1/--/third-party-src/opencv_contrib/README.md

----

## Notes
- openCV 4 is installed at `/usr/local/Cellar/opencv/4.4.0/share/java/opencv4` but IntelliJ can't see that path
  - solution:  softlink from the project directory to that location so you can add the library
  - `$ ln -s /usr/local/Cellar/opencv/4.4.0/share/java/opencv4 opencv4`
- openCV requires JDK14
