## NFC library for Raspberry Pi

This is a Raspberry Pi library for PN532 to use NFC technology.
It works with

+ [NFC Shield](http://goo.gl/Cac2OH)
+ [Xadow NFC](http://goo.gl/qBZMt0)
+ [PN532 NFC/RFID controller breakout board](http://goo.gl/tby9Sw)

### Features
+ Support I2C, SPI and HSU of PN532
+ Read/write Mifare Classic Card
+ Support Peer to Peer communication(exchange data with android 4.0+)

### Getting Started
1. Download [zip file](https://github.com/gassajor000/pyndef/archive/master.zip) and 
extract the 4 folders(PN532, PN532_SPI, PN532_I2C and PN532_HSU) into Arduino's libraries.
2. TODO: Downlaod [Don's NDEF library](http://goo.gl/ewxeAe) and extract it intro Arduino's libraries.
3. Follow the examples of the two libraries.

### To do
+ Card emulation
+ Works with [Don's NDEF Library](http://goo.gl/jDjsXl)

### Contribution
It's based on [Adafruit_NFCShield_I2C](http://goo.gl/pk3FdB). 
[Seeed Studio](http://goo.gl/zh1iQh) adds SPI interface and peer to peer communication support. 
@Don writes the [NDEF library](http://goo.gl/jDjsXl) to make it more easy to use. 
@JiapengLi adds HSU interface.
@gassajor000 ported to python/Raspberry Pi