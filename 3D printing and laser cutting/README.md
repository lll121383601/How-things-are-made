# Output
## Product Background
A century later, the world has achieved the goal of carbon neutrality, and the global climate has entered a phase of stable development. The realization of this achievement is supported by the Global Fundamental Law on Civilization Survival and Ecological Symbiosis as the core legal framework, which also defines two rigid constraints for ecological red lines: first, the global atmospheric carbon dioxide concentration is permanently controlled below 450 ppm; second, the biodiversity conservation volume of each country is incorporated into the civilization survival assessment system, and no development activity is allowed to exceed the "ecological carrying capacity threshold".

## Product Description
Against this backdrop, the portable carbon-based material converter has become a key implementation tool. Developed based on nanocatalysis technology, it is as portable in appearance as a small flashlight. When in use, users only need to point it at industrial waste gas outlets or plastic waste; its built-in micro laser scanner will quickly identify the composition of the substances. Subsequently, through the synergistic effect of high-intensity ultraviolet rays and special catalysts, the device decomposes carbon dioxide in waste gas or plastic waste and re-synthesizes them into high-value biological materials such as degradable plastic particles and biofuel additives. Each use of the device can handle approximately 100 grams of waste, making it easy for environmental law enforcement personnel and enterprise inspection personnel to carry and use at any time, providing strong support for the effective implementation of the legal responsibility for resource recycling.

## The End Product
<p align="center">
	<img src="./product.jpg") alt="size limit image cant be show" width="500">
</p>

## Source file
[laser cutting source file] (https://github.com/lll121383601/How-things-are-made/blob/main/3D%20printing%20and%20laser%20cutting/cutting%20drawing.dwg)

[3D model source file] (https://github.com/lll121383601/How-things-are-made/blob/main/3D%20printing%20and%20laser%20cutting/flashlight.stl)

## Manufacturing process
To create something using 3D printing and laser cutting, you first need an idea💡, and then turn it into a design plan with specific data—like this one.
<p align="center">
	<img src="./draft.jpg") alt="size limit image cant be show" width="500">
</p>
Next, based on your design plan, distinguish the parts suitable for 3D printing from those for laser cutting.
You can draw laser cutting diagrams in your preferred software too, but it must support exporting DXF files. I use AutoCAD.
<p align="center">
	<img src="./cutting drawing.png") alt="size limit image cant be show" width="500">
</p>
Similarly, for 3D modeling, you can use any modeling software you like and are good at, as long as it supports exporting STL files. I use SketchUp. If you want my source files, just click the link above to download.
<p align="center">
	<img src="./flashlight.jpg") alt="size limit image cant be show" width="500">
</p>
After that, import the adjusted 3D model file into UltiMaker Cura. Then you can click the button marked by the red box to adjust the infill density.

Once you’re satisfied with the density, click "Start".
PS:My model in this image is larger than the 3D printer matched by the software. Do not imitate.I later switched to a 3D printer, and this is what it looks like before printing.
<p align="center">
	<img src="./2.png") alt="size limit image cant be show" width="500">
</p> 
Then you can wait beside the 3D printer for it to finish. This way, you can spot any issues promptly if they arise.
<p align="center">
	<img src="./printing.jpg") alt="size limit image cant be show" width="500">
</p> 

Ta-da! This is my super-simplified flashlight!
<p align="center">
	<img src="./3.jpg") alt="size limit image cant be show" width="500">
</p>  

Next, we’ll laser cut a wooden board (for the Arduino mounting plate) and an acrylic board (for the Arduino protection plate). 
First, press the computer’s power button to turn it on. Then open the USB drive, drag the drawn DXF file to the desktop. Right-click the file and select to open it with the LaserCAD software (the icon marked by the red circle).
<p align="center">
	<img src="./4.jpg") alt="size limit image cant be show" width="500">
</p>   
PS: If you don’t see the image initially, just left-click once with the mouse—it usually appears then.
<p align="center">
	<img src="./5.jpg") alt="size limit image cant be show" width="500">
	<img src="./12.jpg") alt="size limit image cant be show" width="500">
</p>   
Next, press Ctrl+A to select all images, then click the red box below to unify all line segments into red, as both panels in my design require cutting.
<p align="center">
	<img src="./6.jpg") alt="size limit image cant be show" width="500">
</p>   
Double-click the red-marked area on the right to adjust parameters. For example, if I cut 2mm wood with my device, set the parameters as: maximum power 98, minimum power 95, speed 20.
<p align="center">
	<img src="./7.png") alt="size limit image cant be show" high="250">
	<img src="./8.jpg") alt="size limit image cant be show" high="250">
</p>   
After editing, press Ctrl A to select all areas of the image, then click the left mouse button on the "Tools" menu and select "Delete Overlapping Lines", "Merge Adjacent Lines", and "Optimize Sorting" in sequence.
<p align="center">
	<img src="./9.jpg") alt="size limit image cant be show" width="500">
	<img src="./10.jpg") alt="size limit image cant be show" width="500">
	<img src="./11.jpg") alt="size limit image cant be show" width="500">
</p>   
Select the image again and click the Load button.
<p align="center">
	<img src="./13.jpg") alt="size limit image cant be show" width="500">
</p>
When the file appears on the cutting machine interface, the laser cutting machine has "received your command". Next, press "Start" and wait quietly for it to finish.
<p align="center">
	<img src="./14.jpg") alt="size limit image cant be show" high="250">
	<img src="./cutting.jpg") alt="size limit image cant be show" width="500">
</p>
The final step is to assemble all the cut parts together.
<p align="center">
	<img src="./product.jpg") alt="size limit image cant be show" width="500">
</p>
