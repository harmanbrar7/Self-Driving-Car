# Self-Driving-Car
A Deep Neural Network car with sensors, avoids traffic and is self improving. 
The machine learning algorithm relies on data structures/math completely with no ML libraries. 

![Screen Shot 2023-11-16 at 11 55 48 PM](https://github.com/harmanbrar7/Self-Driving-Car/assets/89001739/21d30db0-7afb-4bef-bda0-2d237b4a8d2f)

# Introduction

This is a 100% JavaScript framework, with no libraries. Simple HTML and CSS used for styling the roads and car. 

# Design 

The neural network is on the right side. The yellow indicators correspond to turning left, right, moving up and down.

Each part of the project is describing in corresponding js files.

Demo image and video is also provided. 

The car has 100 test cars "underneath it" acting as the brain. It learns from it's mistakes. Any car that hits the traffic or the road boundary, gets a "Damaged" attribute and turns grey. You will see the brain follow along the car that took the best path.

Code ran and tested on VSCode, use the Live Server extension to see the model. Can alternatively use Settings > More tools > Developer Tools on Google Chrome. 

There is a save and erase button to save your best run and the model improves upon itself.

Can add as many traffic cars as you want. The code is fully responsive. 
