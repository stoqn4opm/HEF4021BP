# HEF4021BP
![enter image description here](https://img.shields.io/badge/version-1.0-brightgreen.svg)

HEF4021BP is an Arduino Library with the help of which one can read the serial output of a 8 bit shift register, as the one present in the classic Nintendo NES controller.

# Usage

1. Create a object from type `HEF4021BP ` with the constructor `HEF4021BP(int8_t clock, int8_t latch, int8_t data)`
2. Call the `update()` method of the object every time when you want to read the state of the parallel inputs.
3. Get the button states by calling `int8_t getButtonStates()` method of the object.
4. Do what you want with the input!

For more information you can see the example from the library - "ReadNESController". Also you can checkout [this awesome guide](https://www.allaboutcircuits.com/projects/nes-controller-interface-with-an-arduino-uno/).

# Installation

For detailed instructions check the official guides [here](https://www.arduino.cc/en/Guide/Libraries)

### Manual Installation

1. Put the folder `HEF4021BP` from the repo inside your "custom library" directory. 
	- this directory is different for macOS, Linux and Windows. (checkout the official guides to find out where this directory is)
2. You should now be able to see the new library HEF4021BP in the libraries list.

### Using the `Add Zip Library` option of Arduino IDE

1. Choose the  `Add Zip Library` option from inside `Sketch > Include Library > Add Zip Library...`
2. Select the zip file from the repo `HEF4021BP.zip`
3. You should now be able to see the new library HEF4021BP in the libraries list.



- in case of issues always double check your connections!
