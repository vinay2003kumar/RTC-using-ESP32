# RTC-using-ESP32
Designed a PCB for real time clock(RTC) display.

Real-Time Clock (RTC) using ESP32 involves utilizing the ESP32 microcontroller's capabilities to keep track of time accurately. Here's a typical setup and functionality:

Functionality: The RTC module provides accurate timekeeping even when the ESP32 is powered off. The ESP32 periodically synchronizes its time with the RTC module to maintain accuracy.

Integration: ESP32 interacts with the RTC module via I2C communication protocol, reading and setting the time as needed.

Designing PCB using EasyEDA:

EasyEDA is a web-based tool for designing printed circuit boards (PCBs). Here's a brief guide on designing a PCB using EasyEDA:

- Create Schematic: Use EasyEDA's schematic editor to place components, connect them with nets, and define their attributes (like values, footprints).
  
- PCB Layout: Transfer the schematic to the PCB layout editor. Arrange components on the PCB canvas, considering electrical connections, spacing, and layout rules. Route traces to connect components based on the schematic connections.
  
- Design Rules Check (DRC): Use EasyEDA's DRC tool to ensure that your PCB design meets manufacturing specifications, such as minimum trace width, clearance, and drill size.
  
- Generate Gerber Files: Once satisfied with the layout, generate Gerber files that contain manufacturing instructions for PCB fabrication.
