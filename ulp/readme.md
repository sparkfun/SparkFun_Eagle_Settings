SparkFun Eagle User Language Programs (ULPs)
========================================

These ULPs were developed to aid in various day to day operations at SparkFun. They may or may not be helpful to general users.

* **Include_String.ulp** - Functions used by SparkFun-BOM-Generator.
* **SparkFun-BOM-Generator.ulp** - Scans schematic components and outputs a list of product IDs needed for creating BOMs within the SparkFun ERP software. Also attempts to detect and warn user if there are values that don't match their attribute (for example the product ID is for a 10k but the user has changed the value to 4.7k).
* **SparkFun-CAMmer.ulp** - Creates gerber files from a BRD design. Zips files together using 7za.exe. Checks to see if there are internal layers (up to 4) and outputs appropriate gerbers. Checks to see if there are components on the bottom layer and outputs bottom stencil if requested.
* **SparkFun-Panelizer.ulp** - Creates a given sized panel by copying and pasting a board design with spacing between boards. Works with both 2 layer and 4 layer boards. Automatically loads the correct DRC file (protects against unmasked vias and incorrect polygon pours). Detects if there are overhanging parts that may interfere with the neighboring board. Draws optional v-score indicators and production-friendly frame.
* **SparkFun-PartCreator.ulp** - Parametrically create a device, footprint, and symbol for rectangular ICs. 

License Information
-------------------

The **code** is released under the GPL v3 license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.