# FutekTestBedCircuit

#This Circuit is used to connect the 0-5VDC output of the Futek Load Cell to an i2c message within the 0-3.3V range such that a Raspberry Pi can read it

Relevant People to talk to:

- Riley Peiper
- Megan Giacobetti

Relevant Resources to Use:

- Circuit Layout (see KiCAD Schema File and IMG) 
- The KiCAD Schematic (see KiCAD Schema File)
- The KiCAD PCB Design
- JLC PCB Account [For Ordering] - reach out to @Japmanjeet Singh Gill for login details 
- BOM and CPL Files (See FinalOrderingPackage Folder)


*Note- if cannot login to JLC PCB Account, see the image " JLCPCB COMPONENT PNs " and copy PNs from that file. Note - connectors J1, J2, J3 not placed in the production files. 
- J1 and J2 are through-hole placement and J3 has part shortages in china

To place J3 MOLEX Connector (Mouser PN: 538-203558-0607):
- Get the stencil in the lab
- Apply solder paste to the J3 Connector Area
- Place connector
- Use a hot air heat gun until the solder paste is melted!

To place J1 and J2 Through Hole Connectors (Mouse PN: 651-1984620) 
- Do regular through-hole placement with solder
- Be careful not to solder the pins to the ground layer on the front of the board

**Female Connector for the J3 Molex - Mouser PN: 538-501330-0600**
