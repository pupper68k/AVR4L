# Better AVR
A fork of [AVR4L](https://github.com/abdalmoniem/AVR4L) which aims to be a bit more buildable, and with UI 
tweaks.

![a screenshot of the two panel UI](Main_UI.png)

## About:
AVR4L aims to deliver an easy to use and user friendly Integrated Development Environment for developing Codes for microcontrollers based on Atmel's AVR families. AVR4L is a Creative coding / Integrated Development Environment for Linux operating systems intended for AVR beginners as well as professionals, it has many features from professional IDEs as well as the simplicity of editing.

## Requirements
- gcc-avr, binutils-avr, avr0libc
- gdb-avr
- avrdude

## Installation and Running:

AVR4L works on any system that supports Openjdk 8 and Gradle.
The 'fatJar' task will build an executable jar that should run on any system.
There is script to install it onto any linux system, Windows users can run the Jar 
directly.

### Linux Installation

```
$ git clone https://github.com/abdalmoniem/AVR4L
$ cd AVR4L
$ ./gradlew fatJar
$ cd assets
$ ./install-linux.sh
```

### Windows Installation
- clone git repo with your choice of git client
- open CMD and navigate to repository
- run .\gradlew fatJar
- jar file can be found in build/libs
