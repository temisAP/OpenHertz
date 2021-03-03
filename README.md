# OpenHertz
OpenHertz is a Free, Libre, and Open Source Software (FLOSS) for Hertzian contact calculations.

## Installation:

- No installation is required. Just go to [the website](https://foadsf.github.io/OpenHertz/) and start using it. 

- But if you want to use it locally, download this repository in ZIP format and unarchive it somewhere on your computer. (in a directory where there are no spaced in the path)

<!-- ![Download the zip](pics/download.png) -->
<pre>
<p align="center">
  <img src="pics/download.png" width="350" title="Download the zip">
</p>
</pre>

## Instructions:

- run the `index.html` file
- Choose the type of contact:

    * Sphere-Plane (R)
    * Sphere-Sphere (R<sub>1</sub>-R<sub>2</sub>)
    * Cylinder-Plane (R)
    * Cylinder-Cylinder (R<sub>1</sub>-R<sub>2</sub>)

- If the “Cylinder-Cylinder” option is selected, then the relative orientation of the cylinders needs to be determined:
    * Parallel
    * Perpendicular
    <!-- * Angled (α) -->

- Next, depending on the option selected on the first step, one or two radii should be determined
<!-- - If the two sides of the contact are different materials or the same will be determined next. -->
- Mechanical properties of the material(s) will be given to the software after that. Young elastic modulus (E), Poisson ratio (ν), and Yield strength (σ<sub>Y</sub>) will be given.
- After all, the software will report the results automatically

## FAQ:

- Why not supporting the imperial system of units? Please grow up, US!
<!-- - Why not have a graphical user interface (GUI)? Who knows, maybe in the future it will be added -->
<!-- - Why writing a software in PowerShell? It seems like the only scripting language included in all the Windows corporate machines that the potential audience of this software use. -->

## Glossary:

### Hardness:

- Brinell - HB	
- Rockwell C - HRC
- Rockwell B - HRB
- Vickers - HV