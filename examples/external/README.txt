External libraries
------------------

Examples of using NetworkX with external libraries.

In class
--------
Edit javascript_force.py
(a) Use florentine_families_graph instead of barbell_graph
(b) Calculate communities and centralities for each node
(c) Add these attributes to the nodes (as illustrated in the 2nd link)
(d) Run the script to produce force.json
(Note: in the for loops on nodes and communities, G.node[f] should be G.nodes[f])

Edit force.js
(a) Add a d3.scaleSqrt scale, based on the centrality attribute, to adjust the circle area ("r" attribute) based on its centrality
(b) Add a d3.scaleOrdinal categorical color scale to color the circle ("fill" attribute) based on its community
(c) Change the circle "r" and "fill" attributes to use the scales you created
(d) Run live-server in the folder to view the results via force.html