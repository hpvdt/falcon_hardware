# Falcon Hardware

These are the collected files for all the custom circuit boards for the Falcon aircraft project. All circuits were designed in KiCad 7, and the Gerber files for the circuits as ordered are included.

These systems were primarily designed by several members of HPVDT, overseen by the head of electronics. A block diagram describing their place in the overaching system has been prepared.

![Embedded system block diagram](./Embedded%20Block%20Diagram.jpg)


## Projects

Each folder is for a different electronics circuit/system, which are explained in the table below. 

| Folder | Project | Principal Designer |
| --- | ---| --- |
| `control` | Operates the aircraft's control surfaces | Abdullah Alsafar |
| `flight_stick` | Flight stick, pilots' primary input to the system | Aryan Ghosh |
| `indicator` | Daughter board to indicate control surface status to pilots | Abdullah Alsafar |
| `main_data` | Primary board for data collection of all sensor data | Aryan Ghosh |
| `pressure_sensor_array_atmega` | Differntial pressure array for monitoring wind (ATmega328P) | Jaden Stanshall |
| `pressure_sensor_array_rp` | Differntial pressure array for monitoring wind (RP2040) | Jaden Stanshall |
| `pressure_sensor_array_breakout` | Breakpout for our selected differential pressure sensors | Jaden Stanshall |
| `prop_pitch` | Adjusts the propellor blade pitch and monitors shaft loading | Savo Bajic |
| `servo_regulator` | Distributed servo voltage regulators | Abdullah Alsafar |
| `spar_sensor` | System to monitor the loading of our spars | Alya / Ishi |

![Control system stencil / boards overview](./media/falcon_control_stencil.png)

![Sensing system stencil / boards overview](./media/falcon_sensor_stencil.png)

## Additional Folders

In addition to these projects there are a couple extra folders not directly related to hardware projects present.

| Folder | Purpose | 
| --- | --- |
| `ordered_gerbers` | The manufacturing files actually used for the boards |
| `stencils` | The stencils prepared for the set of boards | 
| `media` | Media files for this repository |