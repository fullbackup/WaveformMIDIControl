# WaveformMIDIControl
This PD (Pure Data) patch will sync Waveform 12 PLAY, STOP and Rewind with your external gear or plugin.
# Installation
Copy both files to your desktop or PD folder
# Controlling Waveform
Setup Waveform to Receive Sync data from a midi BUS on Mac, Jack or Alsa on linux, Or a midi router on Windows.
Setup Pure Data midi out to the Bus or selected output.
Activate MTC on Waveform.
If you press PLAY waveform should respond to it.
# External gear Sync
Add a sencond output to Pure Data on Linux, or select the right output on dropdown menu on PC or MAC.
Setup your gear to accept MIDI time from EXT midi.
Click the EXT toggle box to send MIDI time to your external gear.
* BMP on the control will sync your external gear but not to Waveform. Youy should input the same BPM on waveform and PD MIDI controller before hitting play. 
