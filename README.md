# ESP8266 Hello World Example

Example from [ESP8266_RTOS_SDK](https://github.com/espressif/ESP8266_RTOS_SDK).
Added `CMakePresets.json`

Starts a FreeRTOS task to print "Hello World"

## Build instructions

Open this project in Dev Container, in Visual Studio Code.

Instructions for setting up a Docker container are available in [docker_files](https://github.com/mapi-ng/docker_files) repository.

After opening the project in Dev Container, it can be configured and built using CMakeTools extensions.

For example, after pressing Ctrl-Shift-P in VSCode - following options among others can be used:

- CMake: Configure
- CMake: Build
- CMake: Build Target

When building `flash` target, the script will attempt to flash everything (app and bootloader) to the device.
