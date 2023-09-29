# OpenGLSetup
Template to setup an OpenGL project

1. Put your code, shaders inside "/src/new_project/"
2. Make a "build" directory and then build your new projects inside it.
```
mkdir build ; cd build
cmake ..
cmake --build .
```
3. The output will be in "/bin/new_project/"
```
cd ../bin/new_project
./new_project
```
