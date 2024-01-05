# Ultrasonic Rangefinder: Flutter x Arduino

HC-SR04 Ultrasonic Distance Meter | Flutter With Arduino | Jenkins

## Concept

The Arduino will take the raw data from the HC-SR04 ultrasonic module and convert it into measurement in centimeters and transmit the data to our android phone via the USB OTG.

Then our flutter app will receive the information from the Arduino and display it in radial gauge.

## Components Used
Arduino Uno and HC-SR04 Ultrasonic Module

## Pub packages used in Flutter app
usb_serial and syncfusion_flutter_gauges
