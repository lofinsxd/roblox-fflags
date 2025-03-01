# roblox-fflags

Hey! This repository will guide you through the best fast flags for performance (The Recommended fast flags are downloadable through the config.json file)

# ⚠️ THIS REPO DOES NOT PROMOTE CHEATING FFLAGS. 
IF YOU WANT TO CHEAT IN GAME, DON'T SEARCH FOR FFLAGS AND THINK ABOUT WHAT YOU'RE DOING! Don't ruin the experience for others.

# Getting Started
If you're running Roblox On Linux (Sober):

- *Your config is located at:* ```~/.var/app/org.vinegarhq.Sober/config/sober```
- *We run* ```xdg-open ~/.var/app/org.vinegarhq.Sober/config/sober/config.json``` *and open it through a text editor (E.g. Vim)*.
- *Delete everything and paste in our FFlags.*

# REMOVING TELEMETRY! (Useful)

``` "DFFlagDebugAnalyticsSendUserId": "False",
"DFFlagEnableFmodErrorsTelemetry": "False",
"DFFlagEnableGCapsHardwareTelemetry": "False",
"DFFlagEnableHardwareTelemetry": "False",
"DFFlagEnableLightstepReporting2": "False",
"DFFlagGpuVsCpuBoundTelemetry": "False",
"DFFlagQueueDataPingFromSendData": "True",
"DFFlagSimReportCPUInfo": "False",
"DFIntReportOutputDeviceInfoRateHundredthsPercentage": "0",
"DFIntReportRecordingDeviceInfoRateHundredthsPercentage": "0",
"FFlagAdServiceEnabled": "False",
"FFlagDebugDisableTelemetryEphemeralCounter": "True",
"FFlagDebugDisableTelemetryEphemeralStat": "True",
"FFlagDebugDisableTelemetryEventIngest": "True",
"FFlagDebugDisableTelemetryPoint": "True",
"FFlagDebugDisableTelemetryV2Counter": "True",
"FFlagDebugDisableTelemetryV2Event": "True",
"FFlagDebugDisableTelemetryV2Stat": "True",
```
# Graphics / Rendering Stuff
--- Remove shadows ---

```"FIntRenderShadowIntensity": "0",
```

--- Force MSAA (1, 2, 4, 8) ---

```"FIntDebugForceMSAASamples": "DesiredValue",
```

--- Set Framerate cap ---

```"DFIntTaskSchedulerTargetFps": "ChangeToDesiredValue"
"FFlagTaskSchedulerLimitTargetFpsTo2402": "false",
```

--- Force OpenGL ---

```"use_opengl": true
```

--- Disable PostFX ---

```"FFlagDisablePostFx": "True",
```

--- DISABLE LIGHTNING COMPLETELY ---

```"DFFlagDebugPauseVoxelizer": "True"
```
