# Marker based furniture visualization
This is the repository for our small project for the lecture Augmented Reality at Karlsruhe Institute of Technology in winter term 24/25. The goal is the visualization of 3D furniture models on a smaller scale, so that the best arrangement for a room can be found.

We use the MindAR library with AFRAME as 3D framework. Because of browser security issues (i.e. the browser wouldn't open the main.html) we downloaded the latest mindAR library files from https://www.jsdelivr.com/package/npm/mind-ar?tab=files and import it locally. Basically we build on a working MindAR example provided on the website and load our markers and some simple 3D assets. The markers are generated from https://danilogr.github.io/AR-Marker-Generator/.

The main part of the code is found in the main.html file. First some libraries are imported, then the .mind file containing the marker information is loaded. Afterwards the 3D assets are imported and a camera object is defined for image acquisition. Lastly the 3D assets are assigned to their marker counterpart and position, orientation and scale of the 3D models is set.

