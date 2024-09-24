# longyan-playbook
Setup Longyan as the door strike controller

Longyan uses a collection of three pieces of software

- https://github.com/lugatuic/doorkeeper-controller library to actuate solenoid and script to parse i-Card and determine access
- https://github.com/lugatuic/doorkeeper-driver rust evdev driver to read keycard input
- https://github.com/lugatuic/doorbot-discord py-cord based discord bot to open the door remotely

## Tasks
- Install prereqs
- Installs all three software pieces
- Enables systemd user-services to start the software
