This macro automates the workflow of exporting a SolidWorks Part or Assembly as an STL file and immediately opening it in Cura for 3D print slicing. It eliminates the manual steps of navigating File > Save As, selecting STL format, configuring export options, and then locating and opening the file in Cura — reducing a multi-minute process to a single click.

Key capabilities:
•	Detects and validates solid bodies before export — warns if only surface bodies are found
•	Exports at high-quality custom deviation and angle tolerances for smooth curved surfaces
•	Auto-detects any installed version of Cura from Program Files — no version number hardcoding required
•	Works with both Parts (.sldprt) and Assemblies (.sldasm)
•	Saves the STL file in the same folder as the SolidWorks file by default
•	Forces a model rebuild before export to ensure geometry is current

Please read the documentation for exact details
