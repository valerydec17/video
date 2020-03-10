# OpenGL
## Installation of OpenGL on Ubuntu
`sudo apt-get install freeglut3-dev`
`sudo apt-cache search glut`
`dpkg -L freeglut3-dev`
the output should be as this:
```
/usr/include/GL
/usr/include/GL/freeglut.h
/usr/include/GL/freeglut_ext.h
/usr/include/GL/freeglut_std.h
/usr/include/GL/glut.h
/usr/lib/x86_64-linux-gnu/libglut.a
...
/usr/lib/x86_64-linux-gnu/libglut.so
```

`sudo apt-get install libxmu-dev libxi-dev`

## Compiling the examples on Ubuntu
`g++ example.cc -lglut -lGL -o example`
