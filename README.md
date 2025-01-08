# OBS Recording Sound Notification Script

A simple Python script for OBS Studio that plays custom sound notifications when you start and stop recording.

## Features
- Plays a sound when recording starts
- Plays a different sound when recording stops
- Customizable sound files (.wav format)
- Easy to configure through OBS Scripts settings

## Installation
1. Download the `recording_sounds.py` script
2. In OBS Studio, go to Tools -> Scripts
3. Click the + button and select the downloaded script
4. Configure your sound files in the script settings

## Configuration
1. Prepare two .wav sound files for start and stop notifications
2. In the script settings, set the paths to your sound files:
   - Start Sound File: The sound that plays when recording begins
   - Stop Sound File: The sound that plays when recording ends

## Requirements
- OBS Studio 27.0 or newer
- Python 3.6 or newer installed on your system

## Notes
- Only .wav files are supported
- Make sure your sound files exist at the specified paths
- Keep your sound files short to avoid overlapping

