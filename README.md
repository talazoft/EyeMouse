# EyeMouse

[![OpenCV](https://docs.opencv.org/3.4/opencv-logo-small.png)](https://opencv.org)

EyeMouse is an opensource project to move mouse cursor with eye movement.
This project requires [OpenCV](https://opencv.org/) v4+ to run.

# How to run
### Setup Environment
The environment need to be setup once.

#### Downloading the libraries

```sh
$ sudo apt-get install build-essential xdotool
$ sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev
```

#### Installing OpenCV
This steps will guide you to install OpenCV [here](https://docs.opencv.org/master/d7/d9f/tutorial_linux_install.html). Run this steps if OpenCV does not installed yet.
```sh
$ cd EyeMouse
$ git clone https://github.com/opencv/opencv.git
$ cd opencv
$ mkdir release
$ cd release
$ cmake -D CMAKE_BUILD_TYPE=Release -D CMAKE_INSTALL_PREFIX=/usr/local ..
$ make
$ sudo make install
```

#### Running the project
Run this step for the first time to compile the source code or if you have making any changes to the source code.
```sh
$ cmake .
$ make
$ ./EyeDetector
```

That is all, enjoy

[opencv]: <https://opencv.org/>
