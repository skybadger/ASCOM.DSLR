# ASCOM.DSLR
ASCOM Driver for DSLR Cameras

Discord Channel: https://discord.gg/zPCa9qw

Development environment preparation
1. Install Visual studio 2017/2019
2. Download and install Inno Setup 5.5.8 http://files.jrsoftware.org/is/5/isetup-5.5.8-unicode.exe
3. Install ASCOM platform 6.4 https://ascom-standards.org/Downloads/Index.htm
4. Install ASCOM development components https://ascom-standards.org/Downloads/PlatDevComponents.htm
5. Open visual studio solution, right click on Solution item in Solution Explorer - Restore nuget packages.
6. Now you will be able to build solution

Installer building:
Run build.bat https://github.com/FearL0rd/ASCOM.DSLR/blob/master/build.bat
This script will compile C# project and build installer. Installer will be placed in same folder (filename DSLR.Camera Setup.exe) Note: script is created to work on x64 systems. If you are using x86 - please modify script to correct patch to "Program Filex (x86)" Install path 

Release Notes

5/15/2020 - Added more log fo troubleshooting

5/29/2020 - Fixed Camera detection to work wil multiple cameras

6/01/2020 - New update. I have added Dropdown list for isos to supported applications like SharpCap

6/3/2020 - Some Nikon camera are working as reported by user

6/3/2020 - New Libraw implemented now it can read Canon CR3 and newer formats

6/3/2020 - Picture Preview in the TestApp (Still buggy but you have a preview)

6/10/2020 -PENTAX Cameras are working with this version. (Tested with K-30)

6/10/2020 - New Nikon API started to be implemented (NikonBeta) in the dropdown list.

6/13/2020 - Official Nikon API implemented

6/13/2020 - Old NikonDriver renamed to NikonLegacy in the selection list.

