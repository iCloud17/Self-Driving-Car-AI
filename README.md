# Self-Driving-Car-AI 
Simulator Link: https://icloud17.github.io/Self-Driving-Car-AI/ .

I have created a self driving car AI that learns using Genetic Mutation Algorithm simulator! It operates using the Processing P5.js environment.
Currently, the neural network is a fully connected network with 16 inputs, 24 hidden layer 1 nodes, 18 hidden layer 2 nodes, 12 hidden layer 3 nodes, 8 hidden layer 4 nodes, and finally 6 outputs.

You can view it by running index.html on a local server! Different keys (case insensitive) do different commands:

(By default builder mode is on so to start simulation you first have to toggle builder mode off using 'b'!)

'a': Save your current drawn map as a JSON file

'b': Toggle Buildermode to turn on/off so that you can start building your map

'c': Toggle Checkpoint mode on/off so that you can add checkpoints which the cars will have to cross in order of addition to gain points. Buildermode must be enabled for this.

'd': Upload a map JSON file to load a premade map

'e': When simulation is running, this will toggle whether or not you see entire population or just the firstmost alive car in the population. When youonly see the firstmost alive car, this speeds up simulation speed.

'k': If population is stuck during a generation and not making progress you can press 'k' to manually kill off entire generation instead of waiting for timer to run out.

'l': Toggle which side wall you want to build. In given map example, when building map, first connect all 4 lines of outer walls and then press 'l' to be able to make the inner wall. Buildermode must be enabled for this.
       
        ---------------------
        |  --------------   |
        |  |            |   |
        |  |            |   |
        |  |            |   |
        |  |            |   |
        |  --------------   |
        ---------------------
       
'n': This will save training data statistics as a JSON file.

'm': This will save the best performing car model so far.

'p': This pauses your simulation.

's': This will set the starting position of your cars as well as the direction they will face. Buildermode must be enabled for this.

't': Decreases framerate, i.e, decreases simulation speed.

'u': Uploads the best car model from a JSON file you have previously saved.

'v': Toggles whether you can see the distance lines from car to wall, i.e, see how car sees. When on this will slow down simulation speed.

'w': Toggling this enables/disables waller mode which is when you can start building walls. Buildermode must be enabled for this.

'x': Removes all checkpoints. Buildermode must be enabled for this.

'y': Increases framerate, i.e, increases simulation speed.

'z': Removes all walls. Buildermode must be enabled for this.

Recommended to do Ctrl+Shift+I and go to console to read data feed while using this!
