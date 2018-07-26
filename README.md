# xps-9575-color-profile
### Introduction
I calibrate and profile my XPS 15 2 in 1(9575) UHD laptop using ColorMunki Display, DisplayCAL 3.6 and ArgyllCMS 2.0.
If you find your laptop oversaturated, you can try my [color profile](./FNVDR-LQ156D1%20%231%202018-07-23%2019-19%20D6500%202.2%20M-S%20XYZLUT%2BMTX.icm). I am still learning calibrating and profiling. If you find some issues about my color profile, please let me know.  

If you are doing professional stuff such as photo editing, you may need to calibrate and profile your laptop yourself since we may have different working environments.  

The profile can partly adjust the display for non color managed software. The color is correct only for color managed software, such as Chrome, Firefox, Adobe software, GIMP and so on. You may need to explicitly enable the color management for some of them.  

For color managed video playing, refer to [madvr](http://madvr.com/).  
For color managed gaming, refer to (reshade)[https://reshade.me/].  
### Environment
Laptop: XPS 9575 4k UHD  
BIOS: 1.1.5  
OS: Win10 pro 1709  
Build version: 10.0.16299  
Intel driver version: 24.20.100.6194  
Radeon RX Vega m version: 18.6.1  
Dell Premier Color removed.  
Intel control panel color accuracy: disabled  
### My Calibrating and Profiling Setting
Dell Premier Color removed.  
#### DisplayCAL setting
Color temperature: 6500K Daylight  
Tone curve: Gamma 2.2 Relative  
Calibration speed: medium  
Others: default  
#### Intel control panel setting
Display/Color Setting: Color Accuracy: Disabled  
Others: default

### Result
99.9% sRGB  
99.0% Adobe RGB  
92.7% DCI P3  
[result1.png](result1.png)

