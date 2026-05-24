# Baja-DAQ
A DIY Data Acquisition system, designed for SAE collegiate competition teams and hobbyists. Assemble yourself. Off the shelf parts. open source.

Initial Version:

-ELECTRICAL

--Strain gages or load cells and DCV 0-5V
--through-hole soldering for everything for ease of assembly (except for completion resistors, due to cost)
--COTS breakout boards
--Internal battery sufficient for 4 hours run time
--arduino uno R4 backbone
-DATA AND SOFTWARE
--SD card up to 32GB
--80 Samples/Second average

-MECHANICAL

--3D printed housing
--IP54 rating - Adequate to drive a BAJA car through splashing water and mud without concern.

Future Versions(ideas):

-Architecture

--Central command unit, add in peripherals.
--Expandable/linked clock for multiple modules to sync to a single clock.
--medium channel count (target 10-40 channels of data max)

-Supported Sensors

--Strain gauges, load cells, bridge type accelerometers and pressure sensors
--DCV pressure transducers
--MEMS DC accelerometers
--Potentiometers
--Encoders
--Thermocouples

-Housing

--IP67, (adequate to survive a muddy test, and subsequent hose down)
--Battery powered (full operation for the length of the 4-hour endurance race)

-Data Storage and communication

--Redundant SD cards and possible other storage options
--Wifi to be able to do test and set up
--LORA for live data streaming.
--possible CANBUS architecture

-Other Data Collection

--Arducam
--Built-in IMU
--GPS

-Output modules

--Digital dashboard for live stream data
--DAC for other car level controls.
