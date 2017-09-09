This is for personal use. If need, please go to the following website:

https://github.com/stevenlovegrove/Pangolin

### Required Dependencies ###

* C++11

* OpenGL (Desktop / ES / ES2)

* Glew
 * (win) built automatically (assuming git is on your path)
 * (deb) sudo apt-get install libglew-dev
 * (mac) sudo port install glew

* CMake (for build environment)
 * (win) http://www.cmake.org/cmake/resources/software.html
 * (deb) sudo apt-get install cmake
 * (mac) sudo port install cmake

### Recommended Dependencies ###

* Python2 / Python3, for drop-down interactive console
 * (win) http://www.python.org/downloads/windows
 * (deb) sudo apt-get install libpython2.7-dev
 * (mac) preinstalled with osx

### Optional Dependencies for video input ###

* FFMPEG (For video decoding and image rescaling)
 * (deb) sudo apt-get install ffmpeg libavcodec-dev libavutil-dev libavformat-dev libswscale-dev

* DC1394 (For firewire input)
 * (deb) sudo apt-get install libdc1394-22-dev libraw1394-dev

* libuvc (For cross-platform webcam video input via libusb)
 * git://github.com/ktossell/libuvc.git

* libjpeg, libpng, libtiff, libopenexr (For reading still-image sequences)
 * (deb) sudo apt-get install libjpeg-dev libpng12-dev libtiff5-dev libopenexr-dev

* OpenNI / OpenNI2 (For Kinect / Xtrion / Primesense capture)

* DepthSense SDK

### Very Optional Dependencies ###

* Eigen / TooN (These matrix types supported in the Pangolin API.)

* CUDA Toolkit >= 3.2 (Some CUDA header-only interop utilities included)
 * http://developer.nvidia.com/cuda-downloads

* Doxygen for generating html / pdf documentation.

## Building ##

git clone https://github.com/stevenlovegrove/Pangolin.git
cd Pangolin

mkdir build

cd build

cmake ..

cmake --build .

