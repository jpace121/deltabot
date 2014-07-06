#Basic Structure#

Delta bots are made up of three separated evenly at 120 deg increments.   

Each arm is made up of a "lever" (my vocab) attached to the motor, and a 
"forearm" attached to the end effector.  The arm and forearm are attached by
a universal joint.  The end effector is attached to the forearm by another
universal joint.  (As always, universal joints may be replaces by ball joints.)
    
This basic design gives us three degrees of freedom (our Cartesian Directions).
For rotation, need to add a way for either the end effector to rotate about the
base or the arms to rotate around the base.  Also can get the end effector to
tilt, either directly by moving the end effector or (insert other way here,
think CNC).    
   
Atleast for version 1, I don't think I'm going to worry about the rotation
or tilt.  Rotation seems rather trivial for version 2, and the tilt seems 
rather complex for version 1.

##Other Designs##

Instead of a lever, some designs use an up and down motion using belts. Like
[here](https://www.youtube.com/watch?v=AYs6jASd_Ww).   


