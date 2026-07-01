# Creating a 3D Model

## Table of Contents

- [What is Possible with this Project?](#what-is-possible-with-this-project?)
- [Downloading Data](#downloading-data)
- [Using QGIS to Categorize Data](#using-qgis-to-categorize-data)
- [Creating the 3D Model](#creating-the-3d-model)
- [Troubleshooting the 3D Model](#troubleshooting-the-3d-model)
- [Exporting to Sketchfab](#exporting-to-sketchfab)
- [Optional: Coloring the 3D Model with Blender](#coloring-the-3d-model-with-blender)

## What is Possible with this Project?

This GitHub will walk you through creating a 3D model of your geographic region of interest. From there, you can either export the file to a 3D printer or upload the file to Sketchfab to view it digitally. You can keep the model colorless, or you can add maps and other types of imagery to your 3D model using Blender. This allows you to upload colored versions of your 3D model to view online. <br>

Example of a 3D Printed Model: <br>
<img width="295" height="215" alt="Image" src="https://github.com/user-attachments/assets/817cdfd3-f5af-4923-b746-882821c0dcb0" />

Example of a Digital Model: <br>
<img width="295" height="215" alt="Image" src="https://github.com/user-attachments/assets/f9ec0d91-8692-4cc9-8d58-efbc46bd1b13" />

<br> 

### 3D Projection Mapping
<br>
In the past, I also experimented with 3D projection mapping, which allowed me to project animated videos onto a large, demonstration-sized model. The chosen demonstration video was the 1960 Chilean Tsunami in Hilo, Hawaii. <br><br>

<img width="500" height="400" alt="Image" src="https://github.com/user-attachments/assets/b4cce9ab-ec3c-4381-b96e-caf74ba66ecd" /> <br>

My recommended software for replicating this is MadMapper. MapMap is a free alternative software, but the UI is much harder to work with than MadMapper. Unfortunately, I no longer have access to the projector or model, so I cannot create an in-depth tutorial, but please feel free to contact me if you have any questions. <br>

In the simplest explanation possible, we use Blender to color the model and export an image (or video) taken from above. This image/video must be 2D, NOT 3D. We then use MadMapper to distort the image created in Blender over the physical 3D Model. The ideal conditions for viewing the model setup are with an overhead projector, with the model painted white or with projector paint in a dark room. Some examples of distortion in MapMapper (demo version) is shown below for reference. <br><br>

<img width="346" height="310" alt="Image" src="https://github.com/user-attachments/assets/7b94b823-f0b5-4e64-b03c-940e467507b1" />  <img width="230" height="309" alt="Image" src="https://github.com/user-attachments/assets/0d6fa6cb-ff85-4274-8b1e-18094f8be315" />






## Downloading Data

1. Go to NOAA Digital Coast Data Access Viewer and select Elevation: https://coast.noaa.gov/dataviewer/#/ <br>
2. Use the Search bar or zoom feature to find a general area of interest. <br>
<img width="500" height="250" alt="Image" src="https://github.com/user-attachments/assets/d0742758-3ebf-4952-94e2-c4cbc5b2a3cf" />
<br> If your area is not included in Digital Coast, other sites like OpenTopography are another option. <br>
3. Click on the Draw button in the search bar and outline a box around your chosen area. This will make it so only datasets that you may need are shown. <br>
<img width="500" height="250" alt="Image" src="https://github.com/user-attachments/assets/5c73a328-ef91-4e35-9562-9ce966dd4fec" />



## Using QGIS to Categorize Data

...

## Creating the 3D Model

View .ipynb file.

## Troubleshooting the 3D Model

Since we are developing complex terrain data there will likely be small gaps. The easiest fix it to use Microsofts 3D Builder that comes free on Windows and follow these steps: <br>
1. Import combined_model.stl file <br>
2. It will immediately spot an issue and prompt to fix it. Accept this. <br>
3. File -> Save As -> STL <br>

This should provide you with a 3D model that is ready for printing or uploading to SketchFab.

## Exporting to Sketchfab

...

## Coloring the 3D Model with Blender

[Coming Soon... Gathering Images]


