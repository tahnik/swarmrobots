# src folder

The src folder is here. Create your project with this src. Put your external libraries somewhere else and add them to gitignore

## How to install setup this project in OS X

Use Brew or Macports to download and install OpenCV. I used MacPorts so it might not be similar if Brew is being used.

Create a new JavaFX project in intellij and use the swarmrobots inside workign directory as the project folder.

Go inside the opencv installation folder. For MacPorts it's /opt/local/share/OpenCV . Inside this folder there a folder
called Java. Now you have to make a copy of libopencv_java310.so and rename that copy to libopencv_java310.dylib

Then go to File>Project Structure>Libraries. Here click on the + button to add a new library and navigate to your java
folder inside OpenCV. Then click ok. All the libraries should be imported now.

Here's the link to the image processing tutorial: http://opencv-java-tutorials.readthedocs.org/en/latest/