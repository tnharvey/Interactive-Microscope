## Three.js Interactive Microscope

[View this project live](https://tnharvey.github.io/Interactive-Microscope/)

This is a test project to create an interactive 3D microscope to be used in an Adobe Captivate or Articulate 360 portfolio project. The model was downloaded free from [CG Trader](https://www.cgtrader.com/free-3d-models/science/laboratory/microscope-4a4bdeaa-38ab-4680-ad4a-a9193c55206a) (royalty free).

### Current State:
- Model is loaded, parts are positioned, and raycast is picking up interaction on each of the relevant areas
- Hover results in bloom effect to indicate what new information will be displayed and where the camera will reposition to
- Clicking results in camera movement to focus on the selected object

### Current Issues:
- Damping has a lingering effect that delays interaction when returning to home position
- Textures have cross-hatching, need to smooth them out (probably just my own ignorance)

### Next Steps:
- Adding information layers for each interactive area (e.g. descriptive information for objective lenses, what they do, how to use them in the simulation to get different results)
- Adding labels when in Body view. Possibly add labels for each interactive area that are visible in Home view
- Adjust bloom effect or switch to something closer to an outline effect (might require adding additional mesh that only has outlines and loading has glowing wireframe)
- Creating simulation elements (ability to view through eyepieces and see results of changing focus knob, slide position, etc.)
- Creating a "slide collection" that allows for switching out the slide to view different specimens.
- Adding help features
- Cleaning and restructuring code (separate script and styles)
- Setting up hooks for connecting to Captivate and Storyline
