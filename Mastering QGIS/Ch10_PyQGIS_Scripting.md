
# Chapter 10: PyQGIS Scripting


<!-- toc orderedList:0 depthFrom:1 depthTo:6 -->

* [Chapter 10: PyQGIS Scripting](#chapter-10-pyqgis-scripting)
  * [10.1 Where to learn Python basics](#101-where-to-learn-python-basics)
    * [10.1.1 Tabs or spaces, make your choice](#1011-tabs-or-spaces-make-your-choice)
  * [10.2 Loading layers](#102-loading-layers)
    * [10.2.1 Managing rasters](#1021-managing-rasters)
    * [10.2.2 Managing vector files](#1022-managing-vector-files)
    * [10.2.3 Managing database vectors](#1023-managing-database-vectors)
  * [10.3 Vector structure](#103-vector-structure)
    * [10.3.1 The basic vector methods](#1031-the-basic-vector-methods)
    * [10.3.2 Describing the vector structure](#1032-describing-the-vector-structure)
  * [10.4 Iterating over features](#104-iterating-over-features)
    * [10.4.1 Describing the iterators](#1041-describing-the-iterators)
  * [10.5 Editing features](#105-editing-features)
    * [10.5.1 Update canvas and symbology](#1051-update-canvas-and-symbology)
    * [10.5.2 Editing through QgsVectorDataProvider](#1052-editing-through-qgsvectordataprovider)
    * [10.5.3 Editing using QgsVectorLayer](#1053-editing-using-qgsvectorlayer)
  * [10.6 Running processing toolbox algorithms](#106-running-processing-toolbox-algorithms)
    * [10.6.1 Looking for an algorithm](#1061-looking-for-an-algorithm)
    * [10.6.2 Getting algorithm information](#1062-getting-algorithm-information)
    * [10.6.3 Running algorithms from the console](#1063-running-algorithms-from-the-console)
    * [10.6.4 Running your own processing script](#1064-running-your-own-processing-script)
  * [10.7 Running an external algorithm or command](#107-running-an-external-algorithm-or-command)
    * [10.7.1 Running a simple command](#1071-running-a-simple-command)
  * [10.8 Interacting with the map canvas](#108-interacting-with-the-map-canvas)
    * [10.8.1 Getting the map canvas](#1081-getting-the-map-canvas)
    * [10.8.2 Explaining Map Tools](#1082-explaining-map-tools)
    * [10.8.3 Setting the current Map Tool](#1083-setting-the-current-map-tool)
    * [10.8.4 Getting point-click values](#1084-getting-point-click-values)
    * [10.8.5 Using point-click values](#1085-using-point-click-values)
    * [10.8.6 Exploring the QgsRubberBand class](#1086-exploring-the-qgsrubberband-class)
  * [10.9 Summary](#109-summary)

<!-- tocstop -->


* Learning Python
* Loading rasters by code
* Loading vectors by code from files or database
* Describing vector structure and how to browse and edit features
* Using Processing Toolbox algorithms by code and executing your custom algorithm
* Calling external algorithms
* Interacting with canvas events to draw or pick values from a raster or vector

## 10.1 Where to learn Python basics

This chapter is not intended to give you an introduction to Python programming.
There are a lot of free online resources and MOOC (http://en.wikipedia.org/wiki/Massive_open_online_course) courses on the web.
The main resources can be obtained directly from the Python homepage at https://www.python.org/about/gettingstarted/, where there is a big collection of guides and free books and tutorials.


### 10.1.1 Tabs or spaces, make your choice
## 10.2 Loading layers

### 10.2.1 Managing rasters
* __Exploring QgsRasterLayer__
* __Visualizing the layer__

### 10.2.2 Managing vector files
### 10.2.3 Managing database vectors
## 10.3 Vector structure

### 10.3.1 The basic vector methods
### 10.3.2 Describing the vector structure
* __Describing the header__
* __Describing the rows__

## 10.4 Iterating over features
### 10.4.1 Describing the iterators
## 10.5 Editing features
### 10.5.1 Update canvas and symbology
### 10.5.2 Editing through QgsVectorDataProvider
* __Changing a feature's geometry__
* __Deleting a feature__
* __Adding a feature__

### 10.5.3 Editing using QgsVectorLayer
* __Discovering the QgsVectorLayerEditBuffer class__
* __Changing a feature's attributes__
* __Adding and removing a feature__

## 10.6 Running processing toolbox algorithms
### 10.6.1 Looking for an algorithm
### 10.6.2 Getting algorithm information
### 10.6.3 Running algorithms from the console
### 10.6.4 Running your own processing script
* __Creating a test processing toolbox script__
* __Looking at the custom script__
* __Running the script__

## 10.7 Running an external algorithm or command
### 10.7.1 Running a simple command
## 10.8 Interacting with the map canvas
### 10.8.1 Getting the map canvas
### 10.8.2 Explaining Map Tools
### 10.8.3 Setting the current Map Tool
### 10.8.4 Getting point-click values
* __Getting current Map Tool__
* __Creating the new Map Tool__
* __Creating a map canvas event handler__
* __Creating a Map Tool event handler__
* __Setting up the new Map Tool__

### 10.8.5 Using point-click values
### 10.8.6 Exploring the QgsRubberBand class
## 10.9 Summary


```python

```
