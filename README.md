# Jarvis Assistant V2

Features:
- Hindi/Hinglish-friendly voice commands through Android speech recognition
- YouTube, WhatsApp, Chrome, Instagram, Camera, Settings
- Home, Back, Recent Apps using Accessibility Service
- Volume up/down and mute
- Flashlight on/off
- Call command opens the dialer with the spoken target
- Message/SMS command opens the messaging composer

Example commands:
- "Jarvis, YouTube kholo"
- "Jarvis, WhatsApp kholo"
- "Jarvis, volume badhao"
- "Jarvis, torch on"
- "Jarvis, home jao"
- "Jarvis, back"
- "Jarvis, recent apps"
- "Jarvis, call 9876543210"
- "Jarvis, message I am coming"

Important:
A normal Android app cannot continuously listen for a custom wake word with unrestricted background microphone access on every device. Android versions and OEM battery policies impose restrictions. This build uses the system speech-recognition screen when Listen is pressed. A true always-listening "Jarvis" mode needs a foreground microphone service, wake-word engine, notification, battery-optimization handling and additional Android permissions/constraints.

Calls/messages intentionally use Android system composer/dialer rather than silently sending or placing calls.
