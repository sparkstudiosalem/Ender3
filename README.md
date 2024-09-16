# Ender 3 Standard Operating Procedures (SOP)

## Please read this document in its entirety to learn how to use the Ender 3 3D printer safely and responsibly.
-------------------------------
This document provides step-by-step instructions for operating the Ender 3 3D printer utilizing OrcaSlicer to ensure safe and efficient printing and outlines any rules and procedures that must be followed by any user.

This document will cover:

* Storage and use
* Material-specific machine configurations
* Accessing print profiles and webUI from OctoPrint
* Preparing the printer for print jobs
* Printer-specific features & hazards
* Rules & Misc. Procedures
----------
  Firmware and additional documentation can be found on the [Ender 3 GitHub Page](https://github.com/Creality3DPrinting/Ender-3).
  
  Slicer documentation can be found on the [OrcaSlicer GitHub Page](https://github.com/SoftFever/OrcaSlicer).

-------------

## Storage and Use
While the printer is not in use, it should be stored with the power switched off and all tools and materials properly organized. The power switch is located at the side of the printer near the power input.

Only authorized users should operate the Ender 3 3D printer. Any unauthorized users must be supervised by an authorized user.

## Material-Specific Machine Configuration
The Ender 3 works with a range of materials, but machine setup varies depending on the material.

### Low-Temperature Materials
For materials like PLA, PETG, and TPU, ensure good airflow during printing. Keep the printer in a well-ventilated area, and utilize part cooling fans. These filaments are less prone to warping and can be printed with the bed at lower temperatures.

Low-temp filaments include:
* PLA
* PETG
* TPU

### High-Temperature Materials
It is not recommended to print High temp, "Engeneering materials" on the Ender 3 due to its open build platform and PTFE-Lined hotend.

High-temp filaments include:
* ABS
* ASA
* PC (Polycarbonate)
* Nylon

### Abrasive Materials
It is not recommended to print abrasive filament on the Ender 3 at this time due to its extrude, hotend, and nozzle construction. 

## Accessing Print Profiles and WebUI from OctoPrint
OrcaSlicer has been pre-configured on the designated 3D printing computer at Spark Studio. It provides easy slicing, as well as file transfer and remote print monitoring via OctoPrint, eliminating the need for SD cards or USB drives.

OctoPrint allows for monitoring and controlling print jobs via a web interface. The Ender 3 profile can be accessed from OrcaSlicer and sent to the printer using OctoPrint on the local network. OrcaSlicer can also be downloaded and configured on personal computers to send files and monitor print status from within the space.

OctoPrint can be accessed via the printer’s hostname: "sparkpi-1.local", which is assigned via DHCP. Check the current IP by accessing OctoPrint from the designated computer or through your own device when connected to the local network.

## Preparing the Printer for Print Jobs and Removing Prints
Before printing, the build surface must be properly prepared. The Ender 3 uses a removable magnetic build plate that may need coating with glue stick or hairspray, depending on the filament being used. The bed is made of PEI Coated spring steel.

Make sure the bed is leveled properly before starting the print, and preheat the bed and extruder according to the material’s specifications. OrcaSlicer provides preset profiles with appropriate temperatures, but users should verify settings before printing.

Prints should only be removed from the build surface after the bed has cooled down to ambient temperature. For best adhesion, clean the bed every few prints with isopropyl alcohol, and perform a deep cleaning with soap and water when necessary.

## Printer-Specific Features & Hazards
The Ender 3 is equipped with a heated bed that can reach up to 100°C (212°F). Caution should be exercised when operating or working near the bed, as it can cause burns. Additionally, the stepper motors and belts can move quickly, so avoid placing hands or objects near the moving parts during operation.

## Other Rules & Misc. Procedures
* No part of the Ender 3 (firmware, software, hardware) should be modified without explicit permission from the designated committee or tool director.
* Modifying the printer may void the warranty as per Creality’s guidelines.

## Other Documentation
Further documentation can be found in [Links.txt], which includes additional guides such as the [Ender 3 Official Wiki](https://www.creality.com/pages/3d-printing-support) and [OctoPrint Docs](https://docs.octoprint.org/en/master/).
