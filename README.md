# UC28881_Power_Module
Compact SIL-style power module based on Texas Instruments UC28881 controller, designed in KiCad
## Project Overview
 Design and simulate UC28881-based power supply.
 Verify operation through SPICE simulation in KiCad.
 Create a compact SIL-style PCB optimized for thermal performance and manufacturability.
 Generate Gerber, BOM, and documentation for production.
 ## Repository Structure
/Libraries → Custom KiCad symbols, footprints, and 3D models
/Schematics → KiCad schematic files (.kicad_sch)
/PCB → KiCad board layout files (.kicad_pcb)
/Simulation → SPICE simulation circuits (.cir) and waveform plots
/BOM → Bill of Materials (CSV or Excel)
/Docs → Datasheets, notes, and screenshots
## Tools Used
**KiCad 7.x or later**  
**KiCad SPICE Simulator**  
**GitHub** for version control and project sharing
## Author
Designed and maintained by Oyebisi Hakeem
docs/                      Datasheets, notes, decisions
sch_libs/                  Project symbols (.kicad_sym)
fp_libs/Project.pretty/    Project footprints (.kicad_mod)
3d_models/                 STEP/WRL models
sim/                       ngspice models and waveform plots
pcb/                       Board files/exports
bom/                       Bill of Materials (CSV/XLSX)
scripts/                   Helper scripts (BOM export, checks)
