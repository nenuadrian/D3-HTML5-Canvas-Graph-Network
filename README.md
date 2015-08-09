# D3-HTML5-Canvas-Graph-Network
Example code on how to create and interact with a network of nodes in a canvas element, a graph, using the D3 javascript library which is mainly build for SVG.  Presumably Canvas should be faster in most cases.


However, on my tests on Android, the speed is improved but it's still laggy as Android does not properly support some web technologies. Everything works just that it will skip frame rates.

On laptops, desktops, iOS, etc, it runs very smoothly.

The code also bounds the nodes to the inside of the canvas in a bounding box.

Moreover, D3 transitions are possible thanks to the fact that we'll be generating DOM elements for D3 to run on, outside of the canvas, and then use their attributes on draw.

I'm using the RandomGraph JS library to generate graph data easily.