C++ Makefile Project Template
=============================

Description:
------------
Template small/medium sized C++ project makefile based

Structure:
----------
project/include : header files (*.hpp)
    project/include/external : external modules header files --> gitignored
    project/include/moduleX : internal module X header files

project/src : implementation files (*.cpp)
    project/src/program.cpp : main implementation file
    project/src/moduleX : internal module X implementation files

project/build/objects : object files (*.o) --> gitignored
project/build/apps : executable files (*.exe) --> gitignored

project/makefile

Commands:
---------
`make all` : make with no debug nor release compilation flags (same as `make`)
`make clean` : clean /build directory from files
`make release` : make with release compilation flags
`make debug` : make with debug compilation flags

Run program:
------------
in CppProjectTemplate/ type
`make`
then
`cd build/apps`
then
`./program`

Aknowledgement:
---------------
Arash Patrow
