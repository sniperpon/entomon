# Entomon
Program to chart scorpion robot path, then drive it along that path. User stories:

* As a robot programmer or enthusiast I want to be able to select the program's mode so I can choose how to use it
    * Write the program's basic shell
    * Implement a tool bar or menu with basic edit, save and run functions
* As a robot programmer I want to be able to use the arrow keys to input the robot's path so I can program it
    * Take and refactor old program code
    * Create internal structures to facilitate saving
* As a robot programmer I want to be able to save the path so I can edit it later
    * Write code to save internal structure to file
* As a robot enthusiast I want to be able to load a saved path so I can see it or run it
    * Write code to load internal structure from file and display it
* As a robot enthusiast I want to able to run a path so that the robot does what I want
    * Get brick running with custom firmware
    * Import API into project and create abstractions
    * Implement code to send motor commands per path