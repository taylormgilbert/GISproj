# GISproj
This repo contains the code used to create my GIS project, whereby I plotted spatial data
I got the sahpefile for my map of Africa from this site:https://www.naturalearthdata.com/features/.
The elephant data was from iNat, which I pulled through R, wihtout having to download.
Here is the reference for the shape file with intact forest cover: Potapov, P., Hansen, M. C., Laestadius L., Turubanova S., Yaroshenko A., Thies C., Smith W., Zhuravleva I., Komarova A., Minnemeyer S., Esipova E. The last frontiers of wilderness: Tracking loss of intact forest landscapes from 2000 to 2013. Science Advances, 2017; 3:e1600821.
There is a lot of trial and error within the code, however it should run.
Required packages include: "sf" and "terra" for working with and converting spatial data, "utils" for unzipping zip files, so that i could extract shape files, and "ggplot2" to visualize all the data in a plot (map, with different colour dots for elephants and forest cover).
