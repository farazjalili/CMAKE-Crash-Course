.. sectnum::

===============================================================================
Modern CMake crash course for non-C++ programmers
===============================================================================
:Author: `FarazJalili <https://www.linkedin.com/in/faraz-jalili-80a08669/>`_

.. contents::
   :local:
   :depth: 2
   
   
Fundamental
===============================================================================


Targets
------------
A CMake-based buildsystem is organized as a set of high-level logical targets. Each target corresponds to an executable or library, or is a custom target containing custom commands.
Any target has a collection of properties, which define how the build artifact should be produced and how it should be used by other dependent targets in the project.
