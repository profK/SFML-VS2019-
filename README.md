
# SFML 2.5.1 for Visual Studio 2019 C++

A nuget to install SFML 2.5.1 in a VS2019 C++ project.

SFML is the Simple Fast Multimedia Library, a portable low level library for graphics and game programming. More info on SFML can be found at www.SFML.org

This single package supports x86 and x64 builds in both debug and release build modes. By default, it builds using SFML dynamic libraries (dlls) which are copied into the appropriate build directory.

To use, see https://www.nuget.org/packages/SFML_VS2019/

To build:  
- Download the nuget.exe tool from https://www.nuget.org/downloads
- CD to the project root directory (the one with SFML_VS2019.nuspec in it)
- Execute the following command:  nuget pack

The version number is in the SFML_VS2019.nuspec XML file. You probably want to change it.
Please also release any forked versions with clear descriptions of what is changed in the package description on nuget.org
