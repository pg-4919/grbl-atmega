# An incredibly niche GRBL fork
This is a fork of a fork of GRBL designed for a custom version of a Polargraph wall draw bot.

I forked grbl-polargraph instead of the original grbl since John and Ilaro had already implemented polar coordinates, which we needed as we had a dual-spool system as opposed to dual-axis.

I forget the details as I'm writing this nearly a year after the fact, but essentially all I did was change one line in grbl's config to change the chipset to the stepper control board that we had, an Atmega 328p. We used UGS to control the drawing, and honestly the results weren't half bad.

This code was installed and run for my final Electronics and Robotics project, which I completed together with Eyad Mekki, who did most of the physical design of the robot.
