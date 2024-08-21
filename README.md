# Kicad-Automation-Python
The "KiCad Process Automation" project automates parsing and updating KiCad schematic files using Python and kiutils. It efficiently extracts details like symbol and pin positions and adds custom text annotations based on dynamic rules. The tool enhances efficiency by automating repetitive tasks, reducing manual effort and errors.


symbol position: -> The way the position should print: Symbol Name: R Position of Pin 1 is: X = 33.5, Y = 44.5, Angle = 0 Position of Pin 2 is: X = 50.5, Y = 48.5, Angle = 90

all pins of symbols position and orientation

create a dataframe with above information

All python code needs to be documented as per https://www.sphinx-doc.org/en/master/usage/quickstart.html

================================================================================

Place Text symbol on wire going out from each pin e.g. bhavanagar_priorityID (priorityID number is described below)
For horizontal pin label should be on top of wire
For vertical pin label should be on left of wire
Create priority list of symbols in schematic based on location and sheet order
Symbols in earlier sheet has higher priority - lower number
Symbols in same sheet should be ordered based on left-right and then top to bottom order
================================================================================

Need to develop all automation based on following KiCAD Version

Application: KiCad x64 on x64

Version: (7.0.0), release build

Libraries: wxWidgets 3.2.1 FreeType 2.12.1 HarfBuzz 5.0.1 FontConfig 2.14.1 libcurl/7.83.1-DEV Schannel zlib/1.2.13

Platform: Windows 10 (build 19045), 64-bit edition, 64 bit, Little endian, wxMSW

Build Info: Date: Feb 12 2023 01:35:19 wxWidgets: 3.2.1 (wchar_t,wx containers) Boost: 1.80.0 OCC: 7.6.2 Curl: 7.83.1-DEV ngspice: 39 Compiler: Visual C++ 1934 without C++ ABI

Build settings: KICAD_SPICE=ON
