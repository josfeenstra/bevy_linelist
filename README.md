# bevy_linelist

Render lines in a way that efficient, makes browsers happy, and allows for line thicknesses greater than 1 pixel! 

Forked off `https://crates.io/foresightminingsoftwarecompany/bevy_polyline`, with a few notable changes: 
- [ ] Renders line segments instead of polylines
  - Makes rendering multiple polyline super easy (just append the vertices
  - Makes it possible to render a graph or grid in a staight forward manner  
  - Drawback: doubles the vertex storage for rendering 1 polyline
  - TODO: look into using indices to help mitigate this

- [ ] Renders rounded corners at endpoint. Generally leads to good results at endpoint & in-between points

- [ ] Exposes a scale factor for every vertex for particle effects 

