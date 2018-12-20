# BCN200

El objetivo de este proyecto es mostrar las capacidades de MapServer para representar la cartografía del [CNIG](http://centrodedescargas.cnig.es/CentroDescargas/index.jsp) de España.
Los  datos están en formato shapefile y son accesibles en esta dirección:
[Centro de descargas del CNIG](http://centrodedescargas.cnig.es/CentroDescargas/index.jsp) -> Mapas vectoriales y Bases Cartográficas y Topográficas -> BCN500

# Información

Este proyecto se ha realizado con Mapserver utilizando la herramienta [ScribeUI](http://scribeui.org/). El proyecto pretende crear una base lo más cercana posible a la que se ofrece en la web (Iberpix)

## Servicios OGC

Con el fin de poder mostrar las capacidades de sistema puedes ver En los siguientes enlaces puedes ver las capacidades del sistema para publicar cartografía con el servicio WMS

 - Capabilities: [http://aulageomatica.ua.es:8080/cgi-bin/mapserv?map=/opt/scribeui/workspaces/jose/BCN500/map/BCN500.map&SERVICE=wms&REQUEST=Getcapabilities](http://aulageomatica.ua.es:8080/cgi-bin/mapserv?map=/opt/scribeui/workspaces/jose/BCN500/map/BCN500.map&SERVICE=wms&REQUEST=Getcapabilities)
 - GetMap: [http://aulageomatica.ua.es:8080/cgi-bin/mapserv?map=/opt/scribeui/workspaces/jose/BCN500/map/BCN500.map&SERVICE=wms&REQUEST=Getmap&VERSION=1.1.1&LAYERS=default&SRS=epsg:25830&BBOX=661690,4188342,784513,4311726&FORMAT=PNG&WIDTH=600&HEIGHT=600](http://aulageomatica.ua.es:8080/cgi-bin/mapserv?map=/opt/scribeui/workspaces/jose/BCN500/map/BCN500.map&SERVICE=wms&REQUEST=Getmap&VERSION=1.1.1&LAYERS=default&SRS=epsg:25830&BBOX=661690,4188342,784513,4311726&FORMAT=PNG&WIDTH=600&HEIGHT=600)
 - GetMap con OpenLayers: [http://aulageomatica.ua.es:8080/cgi-bin/mapserv?map=/opt/scribeui/workspaces/jose/BCN500/map/BCN500.map&SERVICE=wms&REQUEST=Getmap&VERSION=1.1.1&LAYERS=default&mode=browse&template=openlayers](http://aulageomatica.ua.es:8080/cgi-bin/mapserv?map=/opt/scribeui/workspaces/jose/BCN500/map/BCN500.map&SERVICE=wms&REQUEST=Getmap&VERSION=1.1.1&LAYERS=default&mode=browse&template=openlayers)

## Ejemplo con Qgis

Si quieres utilizar esta cartografía como un recurso WMS en tu programa de GIS favorito esta es la dirección del recurso:
**http://aulageomatica.ua.es:8080/cgi-bin/mapserv?map=/opt/scribeui/workspaces/jose/BCN500/map/BCN500.map**
Ejemplo de petición
![enter image description here](https://github.com/josemamira/BCN500/blob/master/qgis1.png)
Resultado gráfico
![enter image description here](https://github.com/josemamira/BCN500/blob/master/qgis2.png)

