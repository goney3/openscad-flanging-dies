**Parametric Self-Centering Flanging Dies for Sheet Metal Lightening Holes**

Create perfect, aerospace-grade flanges on your sheet metal lightening holes without spending hundreds of dollars on custom tooling! Now in three shape types: Circle, Stadium, Oval

<img width="200" alt="image" src="https://github.com/user-attachments/assets/a0579dcc-5e84-4b1a-963d-bacdbf48ed11" /><img width="200" alt="image" src="https://github.com/user-attachments/assets/74eea718-841c-4895-87ba-c5d480755082" /><img width="200" alt="image" src="https://github.com/user-attachments/assets/237cfc37-e1c0-4fff-91ec-fceda8d7ae4f" />

These 3D-printable, self-centering flanging dies are designed specifically for thin aluminum (defaulted for 0.016" / 26-gauge) but can be fully customized for your specific scratch-build or sheet metal project.

**How it Works:**
No arbor press or bench vise is required! The male die features a built-in pilot step that perfectly centers your pre-cut aluminum blank. Simply pass a standard bolt (default 3/8") through the center of the dies, add a couple of heavy-duty metal washers and a nut, and tighten with wrenches to press a flawless flange.

**Fully Customizable in OpenSCAD:**
This is a parametric model. Simply open the .scad file in OpenSCAD (free software) and use the built-in Customizer menu to easily adjust the tool to your exact needs:

* Hole Diameter: Match your laser-cut or hole-sawed blanks.
* Flange Angle: Default is 45° (ideal for thin aluminum to prevent tearing).
* Flange Width & Bend Radius
* Bolt Diameter: Size the center hole for whatever hardware you have on hand.
* Base Thickness & Wall Width
* Die Clearance: Defaulted to 0.015" to prevent binding on uncalibrated 3D printers.
* Resolution/Smoothness: Adjust the polygon count for perfectly smooth curves.

**Recommended 3D Print Settings:**
To ensure the dies survive the immense crushing pressure of the bolt, you must print them for compression strength. Standard PLA or PETG filament works perfectly fine for this if sliced correctly!

**Wall Perimeters:** Set your slicer to 5 or 6 outer walls. (Thick walls provide significantly more crush resistance than infill).
**Infill:** Use 40% to 50% infill. A 3D pattern like "Gyroid" or "Cubic" provides excellent structural integrity.
**Orientation:** Print both halves flat on the build plate (the code automatically flips the female die so no supports are needed). This ensures the layer lines run perpendicular to the crushing force.

⚠ **Important Note on Metal Thickness:**
The default variables in this script are optimized for 0.016" thin aluminum. If you are using thicker metal, make sure you understand how to adjust the die clearance, bend radius, and flange depth to prevent tearing, cracking, or creating stress risers in your parts. Always test your dies on a piece of scrap metal first!
