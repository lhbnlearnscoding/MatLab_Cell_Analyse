# 🔬 Cell Analysis Lab (MATLAB)

## Overview
A basic biomedical image analysis example for counting and measuring cells in microscopy images.

## Steps
1. Load grayscale microscopy image  
2. Threshold with Otsu’s method → binary mask  
3. Morphological cleanup (open, close, fill holes)  
4. Label connected components  
5. Measure number and area of cells  
6. Plot histogram of cell sizes

## Run
```matlab
>> cell_analysis
