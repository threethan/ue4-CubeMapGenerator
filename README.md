# ue4-CubeMapGenerator
An easy way to create cube maps from images in ue4, since importing is incredibly finnicky.

This project was made in UE4.25 but should work in future versions without changes.

To open, clone to a folder in your Unreal Projects folder, and open in the editor.
Once opened, 
1. Import you cubemap images as textures (Each image should be a side, sides can be used multiple times and images can have any name)
2. Select the cubemapcube actor from the outliner of the viewport, go to properties -> defaults, and set all relevant images
3. Right-Click cubetarget in the content browser and select 'create static texture'
4. File -> SaveAll
5. RightClick on CubeTarget_Tex and select open in explorer. You can now copy this .uasset into your project.
