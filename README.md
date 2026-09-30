# WCH_Footprints_and_Symbols
A KiCAD library for WCH chips.

**Current KiCAD Version:** 9.x

Mostly going to work on getting all the RISC-V based MCUs added, then I'll 
start working on the other ICs.

This library is for the newer versions of KiCAD and will make use of the
alternate pin functions where possible.

On the subject of the footprints, they are the same as the default library
ones. I've added them to the repo just in case someone is missing them.


## Parts List

### Micro-Controllers

**BLE/WiFi:**

- [X] CH592F
- [X] CH592X
- [X] CH592D
- [X] CH591R
- [X] CH591F
- [ ] CH591D
- [ ] CH583
- [ ] CH582
- [ ] CH581

**CH32L -- Low Power:*


**CH32X--(USB/PD):**

- [X] CH32X033:
    - [X] F8P6 
- [ ] CH32X035:
    - [ ] R8T6 
    - [ ] C8T6 
    - [X] G8U6
    - [ ] G8R6 
    - [ ] F8U6 
    - [ ] F7P6 

**CH32V--(General Purpose/Connectivity):**

- [ ] CH32V002
- [ ] CH32V003
- [ ] CH32V005:
    - [ ] E6R6
    - [ ] F6U6
    - [ ] F6P6
    - [ ] D6U6
- [ ] CH32V006:
    - [X] Kx
    - [ ] E8
    - [X] F8Ux
    - [ ] F8Px
    - [ ] F4U6
- [ ] CH32V203:
    - [ ] F6
    - [ ] F8
    - [ ] G6
    - [ ] G8
    - [X] K6
    - [X] K8
    - [ ] C6
    - [ ] C8
    - [ ] RB
- [ ] CH32V205
- [ ] CH32V208
- [ ] CH32V303
- [ ] CH32V305
- [ ] CH32V307
- [ ] CH32V315

**CH32H --:**


**8051 Based:**

- [ ] CH552E(10pin)
- [ ] CH552G(16pin)
- [ ] CH552T(20pin)
- [X] CH551G(16pin)

### Interface Chips

**USB ICs:**

**Ethernet Adapter Ics:**
These only should be used for micro-controllers that have a MAC built in.

- [ ] CH182

**Ethernet Controller Ics:**
These require user impimentation of the application and protocol stack.

- [ ] CH390D
- [ ] CH390H
- [ ] CH390F
- [ ] CH390L


**Ethernet Protocol Stack Ics:**
These only require users to implement the application code.

- [ ] CH394L
- [ ] CH394Q
- [ ] CH392F
- [ ] CH392T

**Ethernet PHY Ics:**
These require the user to implement:
- App code
- Protocol stack
- MAC controller

- [ ] CH182

**CAN Ics:**

- [ ] CH9431

**I/O Expanders:**

- [ ] CH423
- [ ] CH422
- [ ] CH351

### Analog Chips

- [ ] CH440G
- [ ] CH440P
- [ ] CH440R
- [ ] CH442Q
- [ ] CH442E
- [ ] CH443K
- [ ] CH444G
- [ ] CH444P
- [ ] CH445P

### Power Drivers

- [ ] CH271
- [ ] CH275
- [ ] CH282
- [ ] CH283U/C
- [ ] CH283T

### ESD/overcurrent protection ICs

- [ ] CH213:
    - [X] K
- [ ] CH217
- [ ] CH410
- [ ] CH412

## Organization

Pretty much everything is just in the root directory of the repo.

## Contributing

Make a PR if you want to help out. If you have a specific chip you want 
added feel free to make a github issue for it as well.

## License

BSD 3-Clause License

basically do whatever you want with this.
