# Water body extraction

![raw image](https://raw.githubusercontent.com/junjchen/jarvis/master/water_body_extraction/6030_4_3.png)

## Spectral analysis

Object refelect or absorb sun's radiation varies. The difference can be used to identify spatial objects.

![Spectral signatures of soil, vegetation and water, and spectral bands of LANDSAT 7.](http://www.seos-project.eu/modules/remotesensing/images/Reflexionskurven.jpg)

Water has a high absorption at near infrared wavelengths range and beyond.

![spectral-analysis on water](https://raw.githubusercontent.com/junjchen/jarvis/master/water_body_extraction/spectral-analysis.png)

* Blue: Near-IR1 (BAND7, Wavelength 770 - 895 nm)
* Black: Near-IR2 (BAND8, Wavelength 860 - 1040 nm)
* Blue area overflows black area on the edges caused by turbid water has a higher reflection than clear water

## References

Duong N D. Water body extraction from multi spectral image by spectral pattern analysis[J]. International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, 2012, 39: B8.