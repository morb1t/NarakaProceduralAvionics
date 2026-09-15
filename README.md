# Naraka Procedural Avionics

Procedural avionics core for Kerbal Space Program.

Provides a resizable avionics core based on Procedural Parts with configurable electrical capacity, science storage, sample storage and integrated science instrumentation.

RP-1 is not required.

## Features

- Fully procedural diameter, length and shape
- RealFuels battery tank support
- Configurable science data capacity
- Configurable physical sample storage
- Configurable integrated science instruments
- Progressive science instrument availability
- Flight Telemetry experiment
- Geiger Counter
- Temperature Scan
- Atmospheric Pressure Scan
- Biological Sample Return
- Micrometeoroid Detection
- Mass Spectrometry
- Magnetometer support
- MechJeb integration
- Kerbalism integration
- Realism Overhaul integration
- Probes Before Crew compatibility
- DMagic Orbital Science compatibility
- SpaceDust scanner integration
- Textures Unlimited support

Large or specialized instruments such as telescopes, drills, collectors and other external scientific hardware remain separate parts.

## Requirements

### Required

- ModuleManager
- Procedural Parts

### Optional

- Realism Overhaul
- RealFuels
- Kerbalism
- ROKerbalism
- MechJeb2
- Probes Before Crew
- DMagic Orbital Science
- SpaceDust
- Textures Unlimited

Optional integrations are only applied when the corresponding mod is installed.

## Installation

Extract the archive into the Kerbal Space Program directory.

The resulting path should be:

`GameData/NarakaProceduralAvionics/`

Do not install the repository itself directly into GameData unless the folder structure matches this path.

## Science

The avionics core can provide integrated scientific instruments through Kerbalism's configuration system.

Instrument availability follows technology progression where supported. Instruments add their appropriate mass, cost and electrical requirements.

Science data is stored on the avionics core's configurable hard drive. Physical experiment results use its sample storage.

External Kerbalism science instruments can also use the vessel's available data and sample storage.

## Compatibility

The base part requires Procedural Parts.

RealFuels and Realism Overhaul add RO battery tank types and RO specific spacecraft functionality.

Kerbalism adds configurable science instruments, data storage and physical sample storage.

MechJeb adds MechJeb functionality to the avionics core.

DMagic Orbital Science and SpaceDust integrations use their installed experiment and scanner systems without replacing hardware that should remain external.
