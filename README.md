<div align ="center">
<img src="https://raw.githubusercontent.com/bishwofic/MiuiCamera/tiramisu/res/Icon.png" width="100"/>
<h3>MiuiCamera</h3>
<b>This is a modified MiCamera App to be included while building ROM.<br>
  This is not the full-fledged MiuiCamera consisting potrait, night or other modes.
</div><br>
<h2>Features:</h2>
    
- Photo
- Video
- Square
- Panorama
- Short Video
<br></b>
<h2>Build:</h2>
Clone:

```bash
git clone https://github.com/bishwofic/MiuiCamera -b tiramisu vendor/MiuiCamera
```
  
Add this in your <i>device.mk</i> file.


```bash
# Inherit MiuiCamera
$(call inherit-product, vendor/MiuiCamera/config.mk)
```   
<h2>Snapshots:</h2>
<img src="https://raw.githubusercontent.com/bishwofic/MiuiCamera/tiramisu/res/Preview.png" alt="App" width="280" height="500" />
<br>
