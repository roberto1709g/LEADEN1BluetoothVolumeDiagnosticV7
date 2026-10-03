# LEADEN1 Bluetooth Volume Diagnostic V7

V6 is an isolated Android diagnostic APK. It does not modify the LEADEN1 PWA or VPS.

Purpose:
- inspect Bluetooth adapter state;
- inspect connected A2DP devices;
- inspect Android audio output devices;
- observe STREAM_MUSIC volume changes;
- observe A2DP connection/playing broadcasts;
- compare phone physical volume buttons with the GLASES volume buttons.

On Android 12+, allow Nearby devices / Bluetooth permissions when requested.

Recommended test:
1. Start music with GLASES connected.
2. Open V6 and press ACTUALIZAR.
3. Test phone volume + and - once each.
4. Test GLASES volume + and - once each.
5. Do not change other Bluetooth settings during the test.
6. Save/report the V6 HISTORIAL and the A2DP/AUDIO sections.
