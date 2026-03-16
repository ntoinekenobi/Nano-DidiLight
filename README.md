💡 Nano DidiLight
Nano DidiLight is a lighting control interface that allows you to control the **D::Light lighting software using a **Korg NanoKontrol2 MIDI controller.
This project demonstrates how a compact MIDI controller can be used to control stage lighting parameters such as intensity, submasters, and cues in real time.
Nano DidiLight provides a practical workflow for lighting designers, technicians, and artists who want a portable physical controller for lighting performances.
🎛 Concept
The idea behind Nano DidiLight is simple:
Connect a NanoKontrol MIDI controller to a computer.
Configure the controller using the Korg Kontrol Editor.
Map the MIDI controls to parameters inside D::Light.
Use the faders, knobs, and buttons to control lighting cues live.
Using MIDI messages (Control Change, Notes, etc.), the controller can trigger actions such as:
Submaster intensity
Master brightness
Cue triggers
Flash buttons
Playback controls
Many users configure faders and knobs to control lighting parameters directly through MIDI mapping in D::Light.
🚀 Features
🎚 Control lighting parameters using physical faders
🎛 Map MIDI controls to D::Light functions
⚡ Real-time lighting control
🎭 Suitable for live shows and performances
🧩 Portable and lightweight setup
🖥 Requirements
Hardware:
Korg NanoKontrol2 MIDI controller
Computer (Windows / macOS)
DMX lighting interface
Software:
D::Light
Korg Kontrol Editor
NanoKontrol drivers
⚙️ Setup
1. Install D::Light
Download and install the lighting software.
2. Install NanoKontrol drivers
Install the MIDI driver and connect the controller.
3. Configure the controller
Open Korg Kontrol Editor and configure the controls:
Faders → Control Change
Buttons → Note or Control Change
Transport controls → MMC / MIDI commands
4. Map controls in D::Light
In the MIDI setup:
Enable the MIDI controller
Assign controls to lighting parameters
Test faders and buttons
🎚 Example Mapping
Example control layout:
Control	Function
Fader 1	Submaster 1
Fader 2	Submaster 2
Fader 3	Submaster 3
Knobs	Effects / parameters
Buttons	Flash or cue trigger
Transport	GO / Pause / Back
📸 Project Page
More information about this project:
https://antoinelaloux.com/portfolio/nanodidilight-piloter-dlight-avec-un-nanokontrol-korg/
🔒 License
This project is proprietary software.
Copyright (c) 2026 Antoine Laloux
All rights reserved.
The source code is provided for viewing purposes only.
Unauthorized use, reproduction, or distribution is strictly prohibited.
👨‍💻 Author
Antoine Laloux
Website
https://www.antoinelaloux.com
⭐ If you find this project interesting, feel free to star the repository.
