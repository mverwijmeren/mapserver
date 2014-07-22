Mapserver - Open Source Web Mapping
=============================

`MapServer`_ is an open source platform for publishing spatial data and
interactive mapping applications to the web. It is not a full-featured
GIS system, nor does it aspire to be. In this appliance Mapserver is
combined with Apache, PostgreSQL + PostGIS and PHP, Python and Perl.

This appliance includes all the standard features in `TurnKey LAPP`_,
and on top of that:

- `MapServer`_ with the MapScript modules for PHP, Python and Perl.
- `PostGIS`_, which adds support for geographic objects to PostgreSQL.
- `GDAL/OGR`_, a translator library for raster and vector geospatial
  data formats.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH: username **root**
-  PostgreSQL, phpPgAdmin: username **postgres**

.. _MapServer: http://mapserver.org
.. _TurnKey LAPP: http://www.turnkeylinux.org/lapp
.. _PostGIS: http://postgis.refractions.net
.. _GDAL/OGR: http://www.gdal.org
