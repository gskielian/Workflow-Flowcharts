Workflow-FlowCharts
===================

Preview here:

A flowchart of workflows written in d3.js


Information is encoded in JSON to allow for easy modification of representation later (i.e. standard Model View separation).




This flowchart uses sample code from: http://bl.ocks.org/mbostock/4063550 
for radial-tree rendering.


the collapseable cartesian (rectangular) flowchart template uses sample code from: http://bl.ocks.org/mbostock/4339083

## Directory Structure

.
├── flows
│   └── flow.json
├── index.html
├── radial.html
├── README.md
├── rectangle.html
└── templates
    ├── radial_example.html
    └── rectangle_example.html


* flows
  * workflows are stored in json here
* templates
  * different representation templates compatible with directory tree
* .
  * place actual graphs here for now
