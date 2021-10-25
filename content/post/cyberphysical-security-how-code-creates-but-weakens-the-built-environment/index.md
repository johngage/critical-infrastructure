---
title: "Cyberphysical Security: how code creates, but weakens, the built environment"
subtitle: "Bringing design documents to life: BIM, Brick, SCADA, VHDL"
date: 2021-10-25T21:47:12.349Z
summary: >-
  In computing, logic in hardware and logic in software are conceptually the
  same.  Over time, logic in software moved to hardware for speed. Logic in
  hardware moves to software for testing and verification.


  The built environment has been hardware.....built according to drawings, intuition, and some simulation. That is changing, as future and existing infrastructure is converted to software descriptions to enable coherence, interaction, and extensibility verification.


  In the end, this will be a revolution in maintenance......real-time monitoring of stocks and flows, revealing performance and vulnerability audits.
draft: false
featured: false
image:
  filename: screen-shot-2021-10-25-at-4.14.44-pm.png
  focal_point: Smart
  preview_only: false
---
### How systems are described as executable code

Emergene of metadata systems to develop interoperability among disparate systems, e.g., Brick, ASHRAE 223P;

Need to capture the interrelationships as:

* Composition: what contains what
* Connection, or topology: what connects to what. Needs to capture direction of flow; direction of information; temporal order;

  * Directed Acyclic Graphs for control
  * Cyclic graphs for interactions

Examples of existing systems for thousands of buildings

* Resource Description Framework (RDF): graph nodes; 

###### Chips

###### Boards

###### Computing Hardware

###### Virtual Environments

###### Mechanical devices

###### Built Environment

* Water systems
* Energy systems
* Buildinga

  * Existing communications protocols linking SCADA and other controllers to pumps, valves, transformers, switches:  all the elements of critical infrastructure

    * Building Management Systems: BACnet, Modbus, LonTalk or OPC
    * IoT: Bluetooth, WiFi, Zigbee, Enocean, Thread
  * HVAC: vents, piping, air handling--ASHRAE
  * Lighting
  * Water
  * Electrical
  * Spatial connectivity: stairs, hallways, open spaces, connective areas