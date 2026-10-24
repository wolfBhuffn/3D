# Terminal Card & 360° Turntable Widget:

## Description
A responsive, terminal-styled Card Wrapper embedding a high-precision 360° Image-Sequence Turntable.
Designed as a modular HUD component for the Wolf SaByter interface, this widget delivers hardware-accelerated 3D perspective tilt effects while scrubbing smoothly through 130 pre-rendered rotation frames based on real-time mouse and touch coordinate tracking.

## Architectural Breakdown (For Future Rebuilds)
The Card Wrapper (.TerminalAvatarWidget): The outer visual container. It establishes the terminal aesthetic, live system status telemetry, and responsive 3D CSS perspective tilt.
The Turntable Engine (manifest.json + viewport): The inner functional core. It acts as a sequential frame-swapping engine rather than a heavy WebGL mesh, cycling through the asset array to simulate smooth 360-degree rotation.
