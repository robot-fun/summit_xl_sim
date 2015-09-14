summit_xl_sim
=============

Packages for the simulation of the Summit XL

<h2>summit_xl_control</h2>

New gazebo 1.9 style robot control. Contains the controllers and launch files to start them in gazebo.

<h2>summit_xl_gazebo</h2>

launch files and world files to start the models in gazebo

<h2>summit_xl_robot_control</h2>

<p>control the robot joints in all kinematic configurations, publishes odom topic and, if configured, also tf odom to base_link. Usually takes as input joystick commands and generates as outputs references for the gazebo controllers defined in summit_xl_control. This package permits an alternative way to control the robot motion (4 motorwheels) that by default is carried on by the Gazebo plugin (skid-steer). In the default configuration this package only controls the pan-tilt camera joints.</p>

<h2>summit_xl_sim_bringup</h2>

launch files that launch the complete simulation of the robot
