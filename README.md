# WiFiSwitch

WiFi switch for Alexa/Home, etc.

This is consisted of SSDP, UPnP base class.
And as an example of the delived class, there is WiFi switch.

Currently, for debug/experimental usage, it's implemented to emulate existing devices.

# Dependencies

## General steps to include zip library

On Arduino IDE,

1. Sketch
2. Include library
3. Install Zip library
4. Specify the following zip-ed libraries.

## Time library (by PaulStoffregen-san)

```
$ git clone https://github.com/PaulStoffregen/Time.git Time
$ cd Time
$ git archive HEAD --output=../Time.zip
```

## NTP library (by exabugs-san)

```
$ git clone https://github.com/exabugs/sketchLibraryNTP NTP
$ cd NTP
$ git archive HEAD --output=../NTP.zip
```
