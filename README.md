# Original Roland SD-90 Mac 10.6 and later sound driver

This is the original Roland SD-90 sound driver (audio interface and MIDI) for Mac OSX released around 2009. It still seems to work stably with Ventura 13.2. It supports 32-bit and 64-bit Intel. It is provided as a kernel extension, so if you can't install unsigned kernel extensions or you're on Apple Silicon you're still SOL. Using this requires disabling System Integrity Protection, so it is a bad idea all around for a machine connected to the network. If you need just the MIDI interface you can use the driver at https://github.com/jkl1337/GenericUSBMidi. One day a user mode DriverKit driver may exist.

## Usage
Copy the files in Library/Audio/, Library/PreferencePanes/, and System/Library/Extensions/ to their respective locations on the system root. Ensure permission are correct (owned by root) for the kernel extension. 
