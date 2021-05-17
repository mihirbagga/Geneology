# Getting Started With Tree Plot Package 

This project is for NPM Package 
### IMPORT
##
import Tree from 'mr-tree'
 <Tree
      data={}
      zoom={}
      pcolor=""
      mcolor=""
      chartType=""
      legend={}
      mimage=""
      pimage=""
      />
## Available Props

In this Component , you can pass:

### zoom

zoom ={true}   To enable the zoom 
##
zoom ={false}  this will disable the zoom and set the component at a standard size

### Node color

mcolor ={#f0000f}  to fill the color in the node
##
pcolor ={#f0000f}  to fill the color in the node

### Node image
mimage ={"link"}  to put the image as the node
##
pimage ={"link"}  to put the image as the node

### Node Radius
##
NodeRadius="/value/"  Radius of Node

### Legend Config
##
legend={[{img:" ",name: " " }]}  It will take Array of object

### Right click
##
Right ={callback}  it will take call back
