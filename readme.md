Welcome to the first release of the Software Grasping Synergies GraspModule!
=====================================================================

This module implements grasping synergies in software for the iCub hand, as described in the publication Simplifying Grasping Complexity through Generalization of Kinaesthetically Learned Synergies, G. Cotugno, V. Mohan, K. Althoefer, T. Nanayakkara, ICRA 2014 freely downloadable from Giuseppe's page on thrish.org. 

The module allows to grasp a wide variety of objects like markers, cuboids, and many others described in the paper, using a power grasp or a pinch grip. The module can be easily extended with other grasping primitives by modifying the config files as described in the documentation.

Since publication date, the code has been refactored and re-engineered and is much faster and efficient than before. Please refer to the changelog on the documentation's mainpage for details.

This module differs from other YARP modules as it intensively uses TypeSafeBottles, that is a type safe backward compatible extension of YARP bottles.

The module uses the bottles for parsing the config file, the required components are in the src folder.
It is possible (but not mandatory) to communicate with the module using typesafe bottles, the specifications and components are in the "common" folder. This self-contained folder contains all the required elements to use typesafe bottles in your own projects for communication or file parsing.

Folder/files description:
- app -- configuration files
- cmake -- YARP cmake file
- messages -- TypeSafeBottle release
- src -- header and implementation files
- CMakeLists.txt -- CMakeList file for the Grasper module
- DARWIN_ROOT.ini -- configuration file for YARP version
- mainpage.dox -- doxygen mainpage 
- doc -- documentation folder (in gh-pages branch)
- readme.md -- this file

This module has been developed on YARP version 2.3.22 and has been tested on Linux and Windows.

For queries on this module please contact the authors Giuseppe Cotugno and Kris De Meyer (giuseppe.cotugno@kcl.ac.uk)

Have fun!


The development of this module and the TypeSafeBottles have been supported by EC FP7 DARWIN Project, Grant No. 270138. 
Website: http://darwin-project.eu/

Copyright 2013, King's College London, Released under GPL v2 and later versions.
