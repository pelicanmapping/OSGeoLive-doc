:Author: Glenn Waldron
:Reviewer: Cameron Shorter, Jirotech
:Version: osgeo-live5.5
:License: Creative Commons Attribution 3.0 Unported (CC BY 3.0)

.. image:: ../../images/project_logos/logo-osgearth.png
  :alt: project logo
  :align: right
  :target: http://osgearth.org/


osgEarth
================================================================================

3D Maps Made Easy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

osgEarth is a geospatial SDK and 3D mapping toolkit for OpenSceneGraph_ (OSG) applications.  Just create a simple XML file, point it at your imagery, elevation, and vector data, load it into your favorite OSG application, and go! osgEarth supports all kinds of data and comes with lots of examples to help you get up and running quickly and easily. 

.. _OpenSceneGraph: http://www.openscenegraph.org/

.. image:: ../../images/screenshots/1024x768/osgearth.jpg
  :scale: 50 %
  :alt: screenshot
  :align: right

Core Features
--------------------------------------------------------------------------------

osgEarth makes is easy to deploy whole-earth 3D maps: 

* Create 3D maps based on real data - either offline, or dynamically at runtime 
* Load whole-earth terrains without writing any code 
* Layer imagery to produce high-resolution insets 
* Combine multiple imagery, elevation, and vector data sources on the fly 
* Set up map tile caches to maximize performance 
* Adjust layer opacity for multi-texturing effects 

But osgEarth does more than just render terrain: 

* Drape vector (GIS) data on the terrain 
* Reproject data among different coordinate reference systems 
* Place external models on the terrain with lat/long coordinates 
* Do fast intersection testing
* Integrate your own shaders for custom rendering

Things you can see:

* GeoTIFF imagery and Digital Elevation Model (DEM) files (plus lots of other formats) 
* Vector data like ESRI shapefiles or OpenStreetMap data
* OGC-compliant web mapping data (like WMS_) 
* GIS layers published with MapServer_ or `ESRI ArcGIS Server`_
* Online maps like OpenStreetMap_, `ArcGIS Online`_, or `NASA OnEarth`_

.. _WMS: http://www.opengeospatial.org
.. _MapServer: http://mapserver.org
.. _`ESRI ArcGIS Server`: http://www.esri.com/software/arcgis/arcgisserver/
.. _OpenStreetMap: http://openstreetmap.org
.. _`ArcGIS Online`: http://resources.esri.com/arcgisonlineservices/
.. _`NASA OnEarth`: http://onearth.jpl.nasa.gov


Details
--------------------------------------------------------------------------------

**Website:** http://osgearth.org/

**Licence:** GNU Lesser General Public License (LGPL) 

**Software Version:** |version-osgearth|

**Supported Platforms:** Linux, Mac, Windows

**API Interfaces:** C++

**Commercial Support:** http://web.pelicanmapping.com/priority-support/


Quickstart
--------------------------------------------------------------------------------

* :doc:`Quickstart documentation <../quickstart/osgearth_quickstart>`


