# virus
THIS REPOSITORY CONTAINS A VIRUS THAT RUNS WHEN EXECUTED
Written by Randy Dang, April 2022 

Basic info about virus:
 - Run the virus by executing the "virus" executable
   found in this repository. Make sure execute 
   permissions are on.
 - This virus uses the "sh" shell and runs on Linux 
   machines. Make sure that is installed. 
 - Although this is a virus, it is not a malicious 
   one. All it does is make many copies of itself.

What the virus does: 
 - If running from a directory with subdirectories, 
   it will create many .virus files in all 
   subdirectories, all of which are copies of 
   this virus.
 - If running from a directory with no subdirectories, 
   it will create many .virus files in your home 
   directory (the directory reached when you "cd ~").
   Again, those would all be copies of this virus.

How to repair damage from the virus and all its 
copies:
 - Make sure you are in your home directory.
 - Execute the "clean-virus" executable found in this 
   repository. Make sure execute permissions are on.
 - WARNING: Do not run "clean-virus" if you have 
   important files that happen to have the ".virus" 
   extension. "clean-virus" removes ALL files ending 
   in ".virus".

Acknowledgements:
 - Ming Chow's CS116 class and the foo virus for 
   inspiration
 - Lexi Shewchuk for testing it out 
 - CS40 Lab11 (shell scripting) and the internet at
   large for teaching me how to bash script 
 - Skylar Gilfeather for fixing file path bugs


