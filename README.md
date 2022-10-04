# Quick Resolution Change Script for Windows 10 (11)
The .ps1 scripts will change the following when executed
- Resolution
- Scaling
- Cursor Speed

This script was written to be an easy way to change resolution while running windows in qemu.  
The resolution changed by these scripts doesn't seem to persist across reboots.

## Included Scripts
- `4k.ps1` : Resolution 3860x2160, Scaling 200, Mouse Speed 9
- `1080p.ps1` : Resolution 1920x1080, Scaling 100, Mouse Speed 6
- `1200.ps1`: Resultion 1920x1200, Scaling 100, Mouse Speed 6

## Next Goals
- Find a way to change screen dpi without SetDpi.exe
