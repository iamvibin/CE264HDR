## CE264HDR
An implementation of High-dynamic-range (HDR) imaging technique. First project for Fall 2018 CE264-Computer Vision at UC Santa Cruz

## Motivation
First project for Fall 2018 CE264-Computer Vision at UC Santa Cruz. Implemented Camera Radiometric Calibration, HDR system using two
composition algorithms and geneartion fine tone mapped image. Histograms are also plotted for each of the RG and B channels respectively 
for analysis of changes in pixel values.
 

## OS, Libraries and Language
The code can be compiled in any operating system MAC-OS, Windows. The code is written in python3 and Libraries used are :
1. Opencv
2. Numpy
3. PIL 
4. sklearn
5. Glob

## Scripts 
The project consist of three python notebooks belonging to each part of the project. The notebooks kernels can be refreshed and 
again run to verify the result of the code.
The scripts name and their functionality are decribed below :
1. RadiometryCalibration: 
   Plot the histogram of each R,G & B channels respectively  and regress the function to calculate g values.
2. PlotHistograms:
   This plots th histograms of  the pixel values of each of the channel for three different exposure times which is to be used for
   the HDR generation
3. HDR:
   This script generates HDR using two composite merge algorithms from the three images at different exposure intensities and finally
   map it to generate fine tone-mapped image.
