# x264 iOS build script

This is a shell script to build x264 for iOS apps.

Tested with:

* x264-snapshot-20160814-2245-stable
* Xcode 9.2

## Usage

* Untar the source code into a folder named x264

* To build everything:

        ./build-x264.sh

* To build for arm64:

        ./build-x264.sh arm64

* To build fat library for armv7 and x86_64 (64-bit simulator):

        ./build-x264.sh armv7 x86_64

* To build fat library from separately built thin libraries:

        ./build-x264.sh lipo

* Library and Header Files are in
	./x264-iOS
