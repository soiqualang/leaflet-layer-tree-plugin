# leaflet-layers-tree-plugin

LeafetLayersTreePlugin

This plugin for Leaflet allows to switch layers on and off, structure them in a tree-like way

The list of layers to be displayed can be provided as a JavaScript object where each layer may look like as follows:
<code>
			{
			    "code": "osm",
			    "name": "OpenStreetMap",
			    "active": true,
			    "selectedByDefault": true,
			    "openByDefault": true,
			    "sortOrder": null,
			    "childLayers": [],
			    "selectType": null,
			    "serviceType": "OSM",
			    "params": {"url": "http://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png"}
			}
</code>

Basic usage: https://github.com/bambrikii/leaflet-layers-tree-plugin/blob/master/examples/basic-example.htm

Preview: http://rawgit.com/bambrikii/leaflet-layers-tree-plugin/master/examples/basic-example.htm