# xeokit-simple-viewer

Examples:

XKT
https://xeokit.github.io/xeokit-simple-viewer/?xeokit=latest&type=xkt&url=https://xeokit.github.io/xeokit-sdk/assets/models/xkt/v8/ifc/Schependomlaan.ifc.xkt

GLB/GLTF
https://xeokit.github.io/xeokit-simple-viewer/?xeokit=2.6.61&type=gltf&url=https://xeokit.github.io/xeokit-sdk/assets/models/gltf/MAP/MAP.glb

STL
https://xeokit.github.io/xeokit-simple-viewer/?xeokit=2.6.61&type=stl&url=https://xeokit.github.io/xeokit-sdk/assets/models/stl/binary/spurGear.stl

OBJ
https://xeokit.github.io/xeokit-simple-viewer/?xeokit=2.6.61&type=obj&url=https://xeokit.github.io/xeokit-sdk/assets/models/obj/sportsCar/sportsCar.obj

BIM
https://xeokit.github.io/xeokit-simple-viewer/?xeokit=2.6.61&type=bim&url=https://xeokit.github.io/xeokit-sdk/assets/models/dotbim/BlenderHouse.bim

LAS/LAZ
https://xeokit.github.io/xeokit-simple-viewer/?xeokit=2.6.61&type=las&url=https://xeokit.github.io/xeokit-sdk/assets/models/las/Nalls_Pumpkin_Hill.laz


Query parameters:

xeokit - Which xeokit-sdk version to use, latest or xeokit version number (https://cdn.jsdelivr.net/npm/@xeokit/xeokit-sdk@2.6.61/)
url - address url to model
type - type of model: xkt, las, laz, obj, stl, glb, gltf, bim
rotation - default rotation (x,y,z) default -90, 0, 0
boundingBox - show model bounding box (Boolean)
edges - show model edges (Boolean) default false
colorTextureEnabled - enable color textures (Boolean) default true
dtxEnabled - enable DTX (Boolean) default true
treeViewEnabled - enable TreeView in sidebar (Boolean) default true
treeViewHierarchy - show TreeView hierarchy mode (containment | types | storeys) default containment
transparent - enable transparent background mode (Boolean) default true
backfaces - enable backfaces (Boolean) default true
saoEnabled - enable SAO mode (Boolean) default true
fp64 - 64bit floating point precision for Point Cloud scans (Boolean) default true
cacheBuster - enable cache buster mode (Boolean) default false (This mode adds timestamp to model url)
