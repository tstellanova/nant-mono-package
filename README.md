NAnt packager for Mono
======================

This project provides a packaging script for NAnt. It is aimed to provide a way to update the NAnt installation of the Mono framework on Mac OS X.

The script does:

* The fetching the NAnt source code from GitHub
* The building NAnt targeting the Mono 4.0 profile
* The packaging the result into a package

Here is the result:

![A screenshot of the NAnt installer](https://github.com/Monobjc/nant-mono-package/raw/master/screenshot.png "NAnt Installer")

Note that you will need to install PackageMaker for OSX in order to run this script. PackageMaker is no longer bundled with Xcode.

This is available here: 
[Auxiliary Tools for Developer Preview](https://developer.apple.com/downloads/index.action). An Apple ID login is required. 


