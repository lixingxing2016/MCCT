# Multi-Cue Correlation Tracker
Code for the tracker in the paper **Multi-Cue Correlation Filters for Robust Visual Tracking**, by Ning Wang, Wengang Zhou et. al - to appear in CVPR 2018.

For the MCCT-H tracker, just start Matlab and run the runTracker.m. To run the MCCT tracker with deep features, please download the VGG-19 and compile the Matconvnet following the description in README (in MCCT/model/).

### Contacts
For questions about the code or paper, feel free to contact us.

### Citing
If you find MCCT useful in your research, please consider citing:
```
@InProceedings{DanelljanCVPR2017,  
	Title                    = {Multi-Cue Correlation Filters for Robust Visual Tracking},  
	Author                   = {Ning Wang, Wengang Zhou, Qi Tian, Richang Hong, Meng Wang, Houqiang Li},  
	Booktitle                = {CVPR},  
	Year                     = {2018}  
}
```
### Prerequisites
 - The code is mostly in MATLAB, except the workhorse of `fhog.m`, which is written in C and comes from Piotr Dollar toolbox http://vision.ucsd.edu/~pdollar/toolbox
 - gradientMex and mexResize have been compiled and tested for Ubuntu and Windows 8 (64 bit). You can easily recompile the sources in case of need.

### Acknowledgments
Many parts of this code are adopted from previous works (Staple, HCF).
- L. Bertinetto, J. Valmadre, S. Golodetz, O. Miksik, and P. Torr. Staple: Complementary learners for real-time tracking. In CVPR, 2016.
- C. Ma, J.-B. Huang, X. Yang, and M.-H. Yang. Hierarchical convolutional features for visual tracking. In ICCV, 2015.

