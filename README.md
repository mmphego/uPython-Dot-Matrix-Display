# uPython-Dot-Matrix-Display

![GitHub](https://img.shields.io/github/license/mmphego/uPython-Dot-Matrix-Display.svg)
-----------------------------------------------

**uPython based 8x8 Max7219 4-channel Dot Matrix on an esp8266**

## Story

## Circuit Diagram

## Setup NodeMCU & Tools

Read the [docs](https://docs.micropython.org/en/latest/esp8266/esp8266/tutorial/intro.html)

TL;DR
*   Clone the repo and,
*   Plug in the device to your computer

    **NOTE:** The installation assumes that the port name of device is `/dev/ttyUSB0` else, modify `Makefile` with port name [Hint:`$ ls /dev/tty.*`].
*   Run `make bootstrap`

    **NOTE:** This will install `esptool` and `mpfshell` for communicating with ESP chips and for serial connection with MicroPython boards, Eraze and flash the chip with firmware `esp8266-20190125-v1.10.bin` as well as upload the required files to the ESP.

## Oh, Thanks!

By the way... thank you! And if you'd like to [say thanks](https://saythanks.io/to/mmphego)... :)

✨🍰✨

## Contributing/Feedback

Feel free to fork it or send me PR to improve it.
