NAME: Remote_Executor.vbs

TYPE: Visual Basic Script

PRIMARY LANGUAGE: VBS

AUTHOR: Justin Grimes

ORIGINAL VERSION DATE: 6/8/2018

CURRENT VERSION DATE: 3/11/2019

VERSION: v1.8, Specify full path to cmd.exe in .exec statement.

DESCRIPTION: 

A simple script for executing command prompt commands on domain workstations remotely.

PURPOSE: 
To give administrators the ability to manage endpoints they cannot physically reach.

INSTALLATION INSTRUCTIONS: 
1. Install PSTools binaries into the PSTools folder. Download PSTools: https://docs.microsoft.com/en-us/sysinternals/downloads/pstools
2. Enter your email server address and credentials into sendmail.ini.
3. Run "Remote_Executor.vbs" on your local machine and follow the instructions for inputting a target workstation and command to execute.

NOTES: 
"Remote_Executor.vbs" requires sendmail.exe and PsExec.exe.

Warning emails will still be sent when running in silent mode.
