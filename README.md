# Simple Reflow Controller: Electron App

This is a modified version of the [Simple Reflow Server](https://github.com/lukaslaobeyer/simplereflowserver) that uses the [Electron](http://electron.atom.io/) framework to nicely package everything you need to control the [electronics.kitchen reflow controller](http://electronics.kitchen/reflow) as an application.

## installing
To install the app and control your reflow oven, simply download the prebuild binary for your OS in the [releases](/releases/latest) section.

## building
For building the Sinmple reflow Controller App, make shure, that you have the lastest node.js and npm installed.
To start the actual build process run:
```
git clone https://github.com/lukaslaobeyer/simplereflowserver
cd simplereflowserver
npm build
```
You can find the resulting binary in the `output/` subfolder.