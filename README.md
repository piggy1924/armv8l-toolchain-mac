# armv8l-toolchain-mac
A cross-compiler toolchain for macOS (10.12) host and armv8l-linux-gnueabihf target optimized for cortex-a53 (Raspberry Pi 3).

#### Installation
Checkout to /usr/local/armv8l-unknown-linux-gnueabihf and add /usr/local/armv8l-unknown-linux-gnueabihf/bin to PATH.

#### Components and Versions
* gcc 5.4.0, glibc 2.24, binutils 2.26, gdb 7.11.1 (built with crosstool-ng)
* boost 1.63.0
* OpenCV 3.1.0
* Raspicam (https://github.com/cedricve/raspicam)
* Qt 5
* System libraries (X11, OpenGL) are taken from FedBerry 24
