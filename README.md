CxxExercise Getting started.

Windows
----------------------------
You will need CMake installed (https://cmake.org/) as well as Visual Studio.
Run CMake-gui
	"Where is the source code:" - Navigate to CxxExercise
	"Where to build the binaries:" - Navigate to CxxExercise\build
	Click Configure - default compiler should be OK
	Click Generate
	Click Open Project
In Visual Studio
	Set CxxExercise as startup project
	Read instructions in exercize<N>.cpp and proceed

Linux
----------------------------
You will need CMake and GCC installed - use your package manager
unzip CxxExercise_Preview
from a terminal, cd to the CxxExercise directory (cd ~/CxxExercise or similar)
mkdir build
cd build
cmake ..
make

using your favorite editor - follow the instructions in excersize<N>.cpp
	

