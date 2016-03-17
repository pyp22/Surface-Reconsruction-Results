Surface Reconstruction Results
==============================

3D reconstruction of the church of Echillais (Notre Dame d'Echillais).
See more on: https://fr.wikipedia.org/wiki/%C3%89glise_Notre-Dame_d%27%C3%89chillais

Romuald Perrot's dataset has been used for it and is available from:
https://github.com/rperrot/ReconstructionDataSet/tree/master/EchillaisChurch

PointClouding has been done using openMVG (openMVG_main_ComputeFeatures -m SIFT -p HIGH).
Meshing & texturing has been done using MVE (dmrecon -s2, scene2pset -F2,  meshclean -t 10)