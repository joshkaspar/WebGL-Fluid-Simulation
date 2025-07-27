# WebGL Fluid Simulation

Original project can be found here:

[Play here](https://paveldogreat.github.io/WebGL-Fluid-Simulation/)

<img src="/screenshot.jpg?raw=true" width="880">

## How to add collisions

*🪚 In case it isn't obvious, this is a hack*  

Add a file named `pattern.jpg` to the root directory containing the obstacles you want the particles to collide with. The obstacles Should be black on white. When run locally, browser complained about accessing local files due to CORS policy so I started up a quick server via `python -m http.server 5555` and was able to see the visualization at localhost:5555
