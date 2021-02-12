Bounds on Velocity-dependent Dark Matter–Proton Scattering from Milky Way Satellite Abundance
===========================

Use
-----------
To install the necessary system setup for **Ubuntu 18.04**, run:<br>
`chmod +x setup`<br>
`./setup`<br>

And to build the code, run:<br>
`chmod +x build`<br>
`./build`<br>

Which should yield `server` and `client` executables which can be run via `./server` and `./client`, along with associated flags.<br>

`img/` contains .png files used for testing the code

Limitations
-----------
There is undoubtedly much room for improvement in this code. For one, the setup takes a very long time to come to completion. One way I have attempted to counter this is by allowing the cloning of gRPC submodules to run in parallel (up to 8 submodules at a time). Given more time, I am sure I could find more ways to speed up this step.<br>

Also, I have not had an opportunity to test this code on a fresh build on Ubuntu, but rather by using conda environments, so I cannot say with a high level of certainty that the build process will execute without error. I have done my best to double check that all required build steps are included, but, given more time, I would install a fresh build of 18.04 to ensure that all steps go through properly.<br>

Lastly, while the code in the top directory is written in C++, `dev/` contains a separate, Python implementation of a solution. I've opted to use the C++ implementation for my submission, as it better showcases an understanding of DS/OOP, but the Python implementation should work as well, in case you are interested to check that out. Unfortunately, due to time constraints, I was not able to include build/setup scripts in my Python implementation.

