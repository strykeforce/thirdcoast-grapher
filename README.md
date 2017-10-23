# grapher
This is the 3rd coast telemetry client.  
## Description
Team 2767, Strykeforce developed this application to obtain telemetry information from a robot.  This can be used to optimize control systems for the motor controllers or vision systems.
Coded by Greg Rabick and Sam Rabick
### Development
This program was developed in LabView 2016.

Other add-ons that are required to open the labview code include the following (these can be found by downloading and installing the national instruments VI Package Manager):
* JKI JSON (ver 1.1.10.37)
* JKI REST client (1.2.1.12)

From LabView, open the project file, SamsGrapher.lvproj
Within the project, the main .vi is:  SamsGrapher.vi

### Deployment

#### Executable
The project can be compiled into an executable if you have the national instruments Application Builder add-on installed.  This is a standard add-on that comes with the installation of National instruments Labview if/when you install the development version of Labview that is provided to FIRST teams.

1. From the project window, right click "build specifications".  
2. Select new->Application.
3. fill in the window that appears.  the window is pretty smart about guessing the correct settings to use, so Default settings should work without modification.
4. make sure SamsGrapher.vi is selected as the source.

#### installer
The project window also allows you to create an installer that will install both the grapher application as well as the labview run-time engine (required for computers that do not have the labview development environment installed).  

1. build the executable as defined above first.
2. From the project window, right click "build specifications".
3. select new->installer
4. fill in the window that appears.  the window is pretty smart about guessing the correct settings to use, so Default settings should work without modification.
5. make sure the SamsGrapher.exe is selected as the source file, and ""
