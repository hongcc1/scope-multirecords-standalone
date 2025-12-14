# NI Scope Multirecords (Standalone)
## Overview
NI Scope Multi Records Panel allows you to record multiple waveforms based on trigger settings. 
It also provides options to load settings from NI Scope Session configuration file (.niscopconfig).
This file can be exported using Instrument Studio from a NI scope session. 

It also supports multiple channels acquisition by specifying *Channel Name* like 0-1. Check out the [Channel String Syntax](https://www.ni.com/docs/en-US/bundle/ni-scope-labview-api-ref/page/instr-lib/niscope/niscope-rc/niscope/channel-string-syntax.html).

This VI is written with LabVIEW 2024.

## Front Panel

### Manual configurations

![Front Panel](Pictures/Front%20Panel.png)

### Load configurations from *.niscopeconfig file

![Front Panel](Pictures/Load%20Config.png)

### Export waveforms

![Export Waveform](Pictures/Export%20Waveform.png)
