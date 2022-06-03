# dji_h20t_rpeg_to_tif

## Description

The DJI H20T creates thermal images (infrared) in a format, which is not compatible with current photogrammetric pipelines (e.g., Agisoft Metashape, Pix4D). Moreover, the DJI thermal data should be first calibrated according to emissivity, relative humidity and camera-target-distance. This procedure enables to convert entire folders from *.rtpeg to *.tif format while doing the calibration on the fly. The procedure is based on DJI Thermal SDK.

![single](https://github.com/tejakattenborn/dji_h20t_rpeg_to_tif/blob/main/single_frames.png)

*Examples of single image frames acquired with the DJI h20t.*

![ortho](https://github.com/tejakattenborn/dji_h20t_rpeg_to_tif/blob/main/ortho.png)

*Example of an orthophoto generated from the .tif files created with this procedure.*

Please contact me if you find any bugs or have problems getting the script running:
https://rsc4earth.de/authors/tkattenborn/     https://twitter.com/TejaKattenborn
