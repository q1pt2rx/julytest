# << Program Name >>

    General Description of program function


## Technologies

    - The GNU/Linux Operating system is used to compile and run this software.
    - The program is written in the C++ high level coding language.
    - A makefile is provided to facilitate the build, clean, 
            test and installation processes.
    - Testing is done with <a> bash script(s).
    - The g++ compiler is used to build the software dependancies and executables.



## Build and Installation

The following make commands work inside the root of the 
        application project folder " << project folder >> ":

    To build <all> the executable program(s), enter:
        > make

    To build just one of the executable programs, enter one of:
        > make bin/< etc... >
        
    To compile any of the the source files into object files individually, 
            enter any of the following:
        > make build/main.o
        > make build/< etc... >
        > make build/< etc... >

    To clean all object files and binary applications, enter:
        > make clean

    To test the program(s) using the supplied data files, enter:
        > make test

    To install the program(s) for system wide use, enter:
        > make install     



## Usage

The program takes two(2) command line arguments, 
        any more or less will produce an error

    To run <one of> the program(s) as intended (using relative path if not 
            installed system wide), enter <one of>:
        > ~/<< class >>/<< project folder >>/bin/<< program name >> <file-in> <file-out>



## Contributors

    Humayun Kabir  - Professor
        Application Designer
        Author:
            Application source code 
                    (.h, main.cpp)
            Makefile dependancy hierarchy


    Rocco Ruscitti - Student
        Author:
            Application source code 
                    (.cpp)
            README file information and instructions
            Makefile targets and dependancies:
                    (install, test, diff, disp, run, val)



## License

    No contributors are responsible for the use of any versions of the 
    <names> program(s), 
    or for the invoking of any make commands provided in the makefile found 
    in the root of the project directory, or from following the instructions 
    found in the README.
    
    
    Copyright (C) 2020 Humayun Kabir, Rocco Ruscitti

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
