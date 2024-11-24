# EXP-6: Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

• Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)
• Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)
◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.
• In the terminal, initialise the tools with the following commands if a new terminal is being used.
◦ csh
◦ source /cadence/install/cshrc
• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.
• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

### Synthesis RTL Schematic :
![Screenshot 2024-11-24 184954](https://github.com/user-attachments/assets/4043161a-68b2-4724-b8a8-8508ee21dbbf)


### Area report:
![Screenshot 2024-11-24 185055](https://github.com/user-attachments/assets/804bd03a-d4bf-4407-9f1f-5e7926815cbc)


### Power Report:
![Screenshot 2024-11-24 185151](https://github.com/user-attachments/assets/07a9f2dc-1e55-4e0c-86dd-c7b35e212bee


### Result:
The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
