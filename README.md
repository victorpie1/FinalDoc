# FinalDoc
 Exports autodesk inventor parts and assemblies into a preset file scheme

The code performs the following actions:

Creates a folder on the desktop with a name based on the first four numbers of a property called "Part Number," followed by "Final Doc."

Sets up two subfolders inside the "Final Doc" folder, named "CAD" and "Drawings."

Creates a subfolder with a name derived from the open assembly, in both the "CAD" and "Drawings" folders.

Executes the iLogic rules called "FinalDoc_DWG" and "FinalDoc_STEP."

Moves files with the .step extension from an export folder to the "CAD" subfolder with the corresponding assembly name.

Moves files with the .dwg extension from the export folder to the "Drawings" subfolder with the corresponding assembly name.

Opens subassemblies with a standard Bill of Materials (BOM) structure.

Creates a new subfolder with the same name as the open assembly inside both the "CAD" and "Drawings" folders.

Executes the iLogic rules called "FinalDoc_DWG" and "FinalDoc_STEP" again.

Moves .step files from the export folder to the newly created subfolder.

Moves .dwg files from the export folder to the newly created subfolder.
