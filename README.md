# Web Map of the Amazon Rainforest

## Introduction
In this project, a Web App displaying data of the Amazon Rainforest was developed using Esri's ArcGIS Pro and ArcGIS Online. The idea and part of the implementation were established within an Esri mapathon from the 28.04.-31.04. in Berlin in collaboration with the WWF Germany. The application will be published by the WWF in the following weeks on https://globil.panda.org/ when it has been reviewed. Until then, the video showing its funcionalities will have to subsitute a more interactive user experience. 

https://user-images.githubusercontent.com/116874799/229278450-3a708320-5373-4aab-b940-ab624adf880b.mp4

## Workflow
The Web App was developed using Esri's ArcGIS Pro and ArcGIS Online. These are license-based GIS softwares. The performed workflow is visualised in the following flowchart:

![flowchart](figs/flowchart.png)

First, multiple data sets relevant to the study area and aim of the application were downloaded both from open-access online resources and from the ArcGIS Online Layers, i.e. features hosted by ArcGIS Online. Data acquired from other sources were reprojected to EPSG:3857 reference system using ArcGIS Pro. 
Then, a Web Map was created using ArcGIS Online. All layers that had been downloaded from open-access online resources were uploaded to ArcGIS Online whilst further ArcGIS Online Layers were directly integrated into the map. All layers were grouped into the main categories Biodiversiy, Environment, Socioeconomic and Drivers of Change and Threat and further sub categories. This should later make the usage of the Web App more intuitive and neat. Furthermore, the different layers were styled, either categorized by attribute or just visualised with appropriate colouring. The layers which should be visible when starting the application were toggled visible.

![styling](figs/styling.png)

Lastly, a Web App was created using the ArcGIS Experience Builder. This step is necessary to publish the map and add various functions for a good user experience. The title and application icon, i.e. the WWF panda, were set. Then widgets such as the layer overview, legend, search bar, zooom panel and scale bar were added to the user interface. Also, a pop-up window which is opened at the launch of the application was added, providing information about the study area and idea behind the app.

![experiencebuilder](figs/experiencebuilder.png)

## Results

## Discussion

## Conclusion
