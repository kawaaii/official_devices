SafetyNet passes now.
Fix permissions for PowerOffAlarm.
Fix camera interface on ViLTE calls.
Inherit launch with vendor ramdisk for vAB.
Drop debugfs related sepolicy, mount flags, ownership changes.
Drop unused A-only fstab.
Increase autobrightness light debounce.
Implement a new and modernized double tap to wake sensor(toggle is located in System->Gestures).
Cleanup unused SEPolicy rules.
Drop XiaomiParts as its redundant.
Drop dolby/dirac configs as its redundant.
Enable CLO's Boost Framework.
Inherit common perf components from AOSPA.
Build DisplayFeatures - A package that exposes toggles and QS tiles for HBM and DC Dimming(toggle is located in display).
Disable SF composition prediction model.
Force device to treat 170M as sRGB in SF.
Switch to OSS aptX.
Inherit Adreno Component (updates adreno blobs to V@0530.47).
Drop KProfilesSunny RRO as its redundant.
Drop perf blobs listing since its inherited from common.
Disable Auto Brightness by default to not be blinded during setupwizard.
Update blobs to V14.0.2.0.SKGMIXM.
Implement a new and modernized single tap to wake sensor(toggle is located in YASP->Gestures).
Use jemalloc for libc and camera.
Make wake from notifications separate from Ambient Display [Source].
Add show ambient option for AOSP DT2W, ST2W and lift to wake [Source].
Kernel state: r17a4.
