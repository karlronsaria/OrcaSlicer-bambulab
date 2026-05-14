<div align="center">

<picture>
  <img alt="OrcaSlicer logo" src="resources/images/OrcaSlicer.png" width="15%" height="15%">
</picture>

## This version of OrcaSlicer restores full BambuNetwork support for Bambu Lab printers.

You are not limited to LAN only.  
It works over the internet just like before, through BambuNetwork, with full functionality for normal use and printing.

## Installation

### Windows

Windows requires WSL 2.

Before first launch, open Command Prompt or PowerShell as Administrator and run:

```bat
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```

Restart Windows, then launch Orca Studio.

### Linux

On Linux, a normal installation is enough.

### macOS

Work in progress.


## BMCU

I also encourage you to use BMCU.

You can find BMCU firmware in my repositories.

</div>

## Disclosure

This is a fork of the original OrcaSlicer with BambuNetwork support by [jarczakpawel](<https://github.com/jarczakpawel/OrcaSlicer-bambulab/>) with updates by [FULU Foundation](<https://github.com/FULU-Foundation/OrcaSlicer-bambulab/>) in response to Bambu Lab's copyright trolling campaign.
My primary contribution to this project is to reserve my right under the AGPL license to host my own version of the source code, and to update its documentation to say the following: DOWN WITH THE CHINESE COMMUNIST PARTY! GLORY TO TAIWAN, THE ONE TRUE CHINA!
