# TeleSTERN Rocketry Flight Computer

The TeleSTERN Project is an Open Source Rocketry Flight Computer based on the TeleMega by Altus Metrum.
It contains modifications to an original hardware and software design to fit requirements to European Launch Sites.

The Project has been initiated by the Teams of Space Team Aachen, STAR Dresden and Hochschule Bremen within the Student Experimental Rocket (STERN) Program funded by German Aerospace Center (DLR).

## Usage

The Project File has been created using KiCAD 8.0.
The hardware can be programmed via USB with a customized AltOS software.


## The Design

### Features
- Powerful ARM Cortex-M3 Processor for reliable Performance (STM32L162VDTx)
- Integrated GPS provides precise location tracking (MAX-M10S-00B)
- Accurate Altitude Measurements using Barometric Pressure Sensor (MS5607)
- High-performance IMU for 6-axis Motion Tracking (BMI088)
- Additional MEMS Accelerometer for up to 200 G (ADXL375BCCZ)
- Magnetic Sensing (MMC5983MA)
- Transmitting Real-Time Flight Telemetry to the Ground (CC1200)
- Records detailed Flight Data on Flash Memory for post-flight Analysis
- Up to 6 Pyrotechnic* Outputs for staging, dual-deployment recovery, and other functions
- Compact Design suitable for various rocket sizes and configurations
- **(New!)** Compliance to ESRANGE Safety Guideline: Arming Signal and Radio Silence (tbc)
- **(New!)** Now with RGB LED

_*not limited to explosion based Actuators_


![Front](/render/telestern_v2-2_front.png)
![Back](/render/telestern_v2-2_back.png)


## Licensing
The original hardware and software design has been created by Bdale Garbee and Keith Packard.
All modifications to the original hardware design are licensed under the TAPR Open Hardware License.
All modifications to the original software design are licensed under the GNU General Public License.


## Original Work
- [Altus Metrum TeleMega](https://altusmetrum.org/TeleMega/)
