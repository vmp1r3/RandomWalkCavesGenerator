# Fractal Caves Generator

### INFO:

FCG (Fractal Caves generator) is procedural caves generation system written on C# for Unity3D.

Cave generation process:

<b>1. Cave generation in Matrix object.</b> 
Cave's data is generating inside seperate matrix using properties - size [x * y], pseudorandom seed and etc.
On this stage, matrix is filling recursive. (FractalGenerator)

<b>2. Mesh generation (UnityEngine.Mesh).</b> 
After matrix is generated, EnvironmentGenerator component, generates separete matrices by slicing main matrix to the
separete chunks and provides them to the MeshGenerator component which generates Unity Meshes.

<p align="left">
	<img alt="cave 1" src="http://i.imgur.com/tb4ju2z.png" height="240" width="240">
	<img alt="cave 2" src="http://i.imgur.com/eeDgeGa.png" height="240" width="240">
</p>
Normals and separate chunks.
<p align="left">
	<img alt="normals" src="http://i.imgur.com/qq2VZBG.png" height="240" width="240">
	<img alt="chunks" src="http://i.imgur.com/c3DSrvM.png" height="240" width="240">
</p>


### CONTACTS:
<br>website: http://plasticblock.xyz
<br>E-mail: contact@plasticblock.xyz.

### LICENSE:

<br>Licensed under GPLv3 license or under special license. 
<br>See the LICENSE file in the project root for more information.

<br>FCG Copyright (C) 2016 Jasur "plasticblock" Sadikov.
