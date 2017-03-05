# rubiks-cube-bld

Image processing application that identifies a Rubrik's Cube's current configuration and then proceeds to provide a step by step directions for solving the cube. 

# Concept and Application Workflow
Identifies Rubrik's Cube configuration for a side
Records side based on center color
Notifies user when identification is successful and to turn to the next side (repeat for all 6 sides)
Pushes cube data into solving algorithm
Outputs the steps needed to solve said cube alongside Visualizer

#Dependencies
openCV
