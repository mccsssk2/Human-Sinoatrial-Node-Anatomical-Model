# Human-Sinoatrial-Node-Anatomical-Model

Sanjay Kharche, Ph.D.
August 12, 2017.
Sanjay.Kharche@lhsc.on.ca
============================================================================================

General.
-------

This repository contains the anatomical model data of the human sinoatrial node (SAN) region's 
anatomy. The original computational anatomy was obtained from a previous histology study:

Chandler, N., Aslanidi, O., Buckley, D., Inada, S., Birchall, S., Atkinson, A., Kirk, D., Monfredi, O., 
Molenaar, P., Anderson, R., Sharma, V., Sigg, D., Zhang, H., Boyett, M. and Dobrzynski, H. (2011), 
Computer Three-Dimensional Anatomical Reconstruction of the Human Sinus Node and a 
Novel Paranodal Area. Anat Rec, 294: 970–979. doi:10.1002/ar.21379.

The anatomy was modified in the study by Kharche et al. (provisionally accepted in PloS ONE):

Sanjay R Kharche, Edward Vigmond, Igor R Efimov, Halina Dobrzynski.
Computational assessment of the functional role of sinoatrial node exit pathways in the human heart.
(accepted, August 2017).

The original and modified SAN, well as modified full 3D model anatomy used in Kharche et al. is 
provided in this publicly available git-hub repository. Please cite our papers as given above when using
the anatomy in your scientific/academic studies.

Resolution.
-----------

The 3D model slices are in the X-Y plane whereas the Z axis goes through consecutive planes, please see
Figure 1 of Kharche et al.
The inplane resolution of the model is 0.25 mm x 0.25 mm.
The interplane resolution of the model is 0.5 mm.

6 model anatomy files in legacy VTK format.
----------------------------------------------

The model files are provided in legacy VTK format (ASCII data) to facilitate rapid visualisation as well 
as construction of 3D computational models. The shape of the original SAN is also provided.

* originalSAN.vtk

This is the original SAN anatomy as segmented from histology.

* humanSAN_geometry2.vtk

This is the modified ellipsoidal SAN anatomy used in Kharche et al.

* humanSAN_geometry3.vtk

This is the paranodal area structure in the anatomy.

* humanSAN_geometry4.vtk, humanSAN_geometry5.vtk

These 2 files provide distribution of atrial tissue in the anatomy.

* humanSAN_geometry6.vtk

This file has the SAN border zone with exit pathways.
