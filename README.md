# zCFD_Utils
Utilities for working with zCFD Solver

Tom Wainwright

University of Bristol

tom.wainwright@bristol.ac.uk

## Current modules:

* mesh_utils:
  * Unpack and manipulate both ZCFD and CBA meshes
  * Convert meshes to tecplot .plt format
  * Extract surfaces for RBF mesh deformation
  * Convert single and multiblock CBA meshes into zcfd format
  * Convert CBA meshes into plot3D format to import to pointwise

* zConverge
  * Donwload and plot zCFD report file to track convergence from remote cluster

* test_suite
  * Contains some demos of how to use the various functions described above

* UoB_coupling
  * Open source python script for running custom FSI scheme

* py_rbf
  * python implementation of RBF mesh deformation- currently only uses full RBF and is applied for stuctural-aero surface coupling, not volume mesh deformation

* Examples included:
  * Omesh.blk
    * Single block
    * 2D
    * NACA0012 Aerofoil
    * O- Mesh topology
  * Cmesh.blk- Multiblock
    * 3 Blocks
    * 2D
    * RAE2822 Aerofoil
    * CH- Mesh topology
  * MDO_125K.blk
    * 8 Blocks
    * 3D
    * BRITE-EURAM MDO wing
    * CH- Mesh topology
  * CT0_250K.blk
    * 36 Blocks
    * 3D
    * Caradonna-Tung rotor, 0 &deg
    * CH- Mesh attached topology with H expansion blocks