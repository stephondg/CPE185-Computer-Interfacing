# CPE185-Computer-Interfacing
Introduction
For my final project, I chose to design a motion detection camera. For this
project, I would have to combine the previous five labs I designed and completed. The
only additional task I had to complete for this project was to create a base and modify
the code to implement all five parts together. As I had already confirmed the individual
labs worked, i had to rewrite the signals that each component would take. For example,
instead of the PIR sensors lighting up LEDs in the zone detected, the signal would have
to move the servo to point in that zone. This was not extremely difficult specifically
because I was only integrating five parts together whereas a seperate group project
would have to combine and effectively implement approximately 20 separate parts
together.

Project Implementation
I first began merging the servo and PIR sensor code, which proved to be simple
enough. I changed the case statements from turning on LEDs to write the position for
the servo to rotate to. I then modified the code to have the LCD print out specific
messages only during certain cases, i.e. only print motion detected when the PIR
sensors detect motion, display the start up sequence only when the program starts or is
reset, etc. Next I had to allow the IR remote to interface with the camera as well, and
force the camera into a continuous motion detected mode. The camera would have to
point in the direction indicated by the motion and move to the next zone when directed.
