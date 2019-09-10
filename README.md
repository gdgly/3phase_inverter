# Power Inverter Development Repository

### Features

- The 3-phase 30A@450V power inverter with control board for research purposes;
- This inverter has built-in measurements of AC currents, AC voltages and DC bus voltage;
- The inverter is based on infineon IPM IKCM60F30GA module (a ultra low-cost module, with integrated drivers);
- The control board is based on XMC4500 Relax (lite) kit, a well known board in UP Laboratory of Power Electronics;
- Reduced cost of hardware (around 100€);

### How to use

- TODO

### TODO

- Define functional requirements of this project
- Create BOM for 10 boards (expecting 1000€)
-
- Create "how to use" manual 

### DEMO

#### V2
<a href="url"><img src="https://raw.githubusercontent.com/vitormorais/3phase_inverter/master/z_junk/img3.jpg" width="60%" ></a>

#### V1
<a href="url"><img src="https://raw.githubusercontent.com/vitormorais/3phase_inverter/master/z_junk/img1.png" width="40%" ></a>
<a href="url"><img src="https://raw.githubusercontent.com/vitormorais/3phase_inverter/master/z_junk/img2.jpg" width="40%" ></a>


------------



### Folder structure

| FOLDER   | DESCRIPTION  | comments  |
| :------------ | :------------ | :------------ |
|  1. Functional  |  Documentation folder for functional requirements of this project |   |
|  2. Hardware PCB  |  Development folder for the PCB hardware  |   |
|  3. Design  |  Documentation for the hardware design requirements and BOM   |   |
|  4. Software_WS  |  Development folder having the DAVE workspace for XMC4500 programming  |    |
|  5. Implementation | Documentation and simulation of the simulated models/algorithms |  |
|  6. Testing&Validation | Documentation of the product testing |   |
|  z_junk   |  folder for not-structured content |   |    



### Folder structure (tree)

```bash
├── 1. Functional
├── 2. Hardware PCB
│   ├── CAMtastic_controlo_rev21.Cam
│   ├── CAMtastic_controlo_rev22.Cam
│   ├── CAMtastic_inversor_rev21.Cam
│   ├── CAMtastic_inversor_rev22.Cam
│   ├── History
│   ├── PCB_controlo_rev2.zip
│   ├── PCB_inversor_rev2.zip
│   ├── __Previews
│   ├── accets
│   ├── controlo_rev2.PcbDoc
│   ├── controlo_rev2.PrjPcb
│   ├── controlo_rev2.PrjPcbStructure
│   ├── controlo_rev2.SchDoc
│   ├── debug.log
│   ├── inversor_rev2.PcbDoc
│   ├── inversor_rev2.PrjPcb
│   ├── inversor_rev2.PrjPcbStructure
│   ├── inversor_rev2.SchDoc
│   ├── vmorais_libraries.PcbLib
│   └── vmorais_libraries.SchLib
├── 3. Design
├── 4. Software_WS
│   └── OL_VSC_vitor
├── 5. Implementation
├── 6. Testing&Validation
├── README.md
├── folder_structure_binary.txt
└── z_junk
    ├── img1.png
    ├── img2.jpg
    └── img3.jpg
```
