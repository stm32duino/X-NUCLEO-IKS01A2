# X-NUCLEO-IKS01A2

The X-NUCLEO-IKS01A2 is a motion MEMS and environmental sensor expansion board for the STM32 Nucleo.
It is equipped with Arduino UNO R3 connector layout, and is designed around the LSM6DSL 3D accelerometer and 3D gyroscope, 
the LSM303AGR 3D accelerometer and 3D magnetometer, the HTS221 humidity and temperature sensor and the LPS22HB pressure sensor.
The X-NUCLEO-IKS01A2 interfaces with the STM32 microcontroller via the I²C pin, and it is possible to change the default I²C port.

## Examples

There are several examples with the X-NUCLEO-IKS01A2 library.
* X_NUCLEO_IKS01A2_HelloWorld: This application provides a simple example of usage of the X-NUCLEO-IKS01A2 
Expansion Board. It shows how to display on a hyperterminal the values of all on-board MEMS and environmental sensors.
* X_NUCLEO_IKS01A2_6DOrientation: This application shows how to use X-NUCLEO-IKS01A2 to find out the 6D orientation and 
display data on a hyperterminal.
* X_NUCLEO_IKS01A2_DoubleTap: This application shows how to detect the double tap event using the X-NUCLEO-IKS01A2.
* X_NUCLEO_IKS01A2_FreeFall: This application shows how to detect the free fall event using the X-NUCLEO-IKS01A2.
* X_NUCLEO_IKS01A2_MultiEvent: This application shows how to detect free fall, tap, double tap, tilt, wake up,
6D Orientation and step events using the X-NUCLEO-IKS01A2.
* X_NUCLEO_IKS01A2_Pedometer: This application shows how to use X-NUCLEO-IKS01A2 to count steps.
* X_NUCLEO_IKS01A2_Tap: This application shows how to detect the single tap event using the X-NUCLEO-IKS01A2.
* X_NUCLEO_IKS01A2_Tilt: This application shows how to detect the tilt event using the X-NUCLEO-IKS01A2.
* X_NUCLEO_IKS01A2_WakeUp: This application shows how to detect the wake-up event using the X-NUCLEO-IKS01A2.

## Dependencies

The X-NUCLEO-IKS01A2 library requires the following STM32duino libraries:

* STM32duino LSM6DSL: https://github.com/stm32duino/LSM6DSL
* STM32duino LSM303AGR: https://github.com/stm32duino/LIS3MDL
* STM32duino HTS221: https://github.com/stm32duino/HTS221
* STM32duino LPS22HB: https://github.com/stm32duino/LPS22HB

## Documentation

You can find the source files at  
https://github.com/stm32duino/X-NUCLEO-IKS01A2

The X-NUCLEO-IKS01A2 datasheet is available at  
http://www.st.com/content/st_com/en/products/ecosystems/stm32-open-development-environment/stm32-nucleo-expansion-boards/stm32-ode-sense-hw/x-nucleo-iks01a2.html
