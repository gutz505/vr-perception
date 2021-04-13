# vr-perception
A-Frame based application to explore perception with virtual reality

The A-Frame framework is used to create a virtual environment which can be explored either via virtual reality system or stationary monitor.

In the study dektopMain.html is viewed via computer monitor while vrMain.html is viewed via Oculus Rift S head-mounted display.



The application uses the following libraries, imported at the start of desktopMain.html/vrMain-html: aframe; aframe-extras.loarder; aframe-curve-component; aframe-along-path-component.

gltf-models are imported using aframe-extras.loader. A predefined traversal path is created in the virtual environment by locating curve-points using aframe-curve-component. In order to animate the virtual camera following the path aframe-along-path-component is used with the traversal time set to 120000 milliseconds.

The asset manager is used to load the scene including geometry and texture data of displayed 3D-objects. gltf-models can be used withing A-Frame using the aframe-extras.loarder library. 
