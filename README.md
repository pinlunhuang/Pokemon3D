# Pokemon3D

Introduction
------------

- iOS App Using Apple ARKit to show Pokenmon AR 3D Model on the Detected Pokemon Card Plane
- Use Cute Eevee as example
- Feel free to fork or clone this project!

Pre-requisites
--------------

- Pokemon Card Picture Material from: http://limitlesstcg.com/tools/proxies/
- Pokenon 3D Model Material from: http://roestudios.co.uk/project/3d-pokemon-models/
- Use Mac Xcode Command Line Tool: USDZ_CONVERTER to transfrom obj file into usdz file
- cmd: xcrun usdz_converter <your_obj_filepath> <output_usdz_filepath>
- Example: xcrun usdz_converter /Users/<username>/Desktop/pikachu.obj /Users/<username>/Desktop/pikachu.usdz
- usdz_converter cmd info: https://imgur.com/a/CAGppb1
- Or you can choose open-source software called "Blender" to transform blend file in to dae file

- Second Step: using Xcode built-in converter to make scn file conversion (dae & usdz files are both supported)

- Blender Offcial Website: https://www.blender.org/

Screenshots
-------------

- When the card plane not detected ↓
<img src="https://github.com/pinlunhuang/Pokemon3D/blob/master/Pokemon3D/Screenshots/IMG_0417.PNG" width="414" height="896" />

- When the card plane is detected ↓
<img src="https://github.com/pinlunhuang/Pokemon3D/blob/master/Pokemon3D/Screenshots/IMG_0418.PNG" width="414" height="896" />
