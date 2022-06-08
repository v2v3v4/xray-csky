# xray-csky
![Logo](https://i35.fastpic.org/big/2012/0323/46/ae7b8d2f5f0ad39d2db7fcbc48fbfc46.jpg "Logo")

Vanilla S.T.A.L.K.E.R. Clear Sky Engine:
* Ported source code to VS 2022 17.2.2 (C++14 mode)
* Removed STL Port dependence
* Removed DXMath dependence into xrEngine 
* DX10 use D3DCompiler library 

Problems:
* HWCaps: disabled detecting AMD GPU count. X-Ray used old ATI library. Need implement by AMD Crossfire detect system. 
