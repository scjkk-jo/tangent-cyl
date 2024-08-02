

# Spherical shell and tangent cylinder analysis

This project is designed to import, convert, and process multiple timesteps of simulation data to compute and output various diagnostic properties for both the spherical shell and the cylinder. It encompasses the entire workflow from data organization to grid creation, interpolation, gradient computation, and calculation of physical properties such as kinetic energy, vorticity energy, length scales, Reynolds number, and Nusselt number.

## Overview

The code processes simulation data in spherical coordinates and interpolates it into cylindrical coordinates to perform detailed analysis. The primary goal is to understand the dynamics within a spherical shell and its tangent cylinder, offering insights into energy distribution, flow characteristics, and thermal properties.

### Key Features

Data Organization: Organizes input simulation data for further processing.<br>
Grid Creation: Generates grids for spherical and cylindrical coordinates.<br>
Interpolation: Interpolates data from spherical to cylindrical grids.<br>

### Physical Properties Calculation:

Kinetic Energy (KE)<br>
Energy of Vorticity (EOV)<br>
Length Scales (L)<br>
Reynolds Number (Re)<br>
Nusselt Number (Nu)<br>
Results Output: Saves computed properties into .npy files for further analysis.<br>



### Usage

To run the main function, call: <br>
<br>
process_timesteps() <br>
<br>
This function integrates all the steps, processes the data, and outputs the diagnostic properties.

### Prerequisites

numpy<br>
scipy<br>
os<br>
time<br>


### Contributions

Contributions to enhance the functionality, efficiency, or readability of this code are welcome. 

### License

This project is licensed under the MIT License.
