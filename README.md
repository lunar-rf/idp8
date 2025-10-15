# idp8
```
    ________  ____  ____ 
   /  _/ __ \/ __ \( __ )
   / // / / / /_/ / __  |
 _/ // /_/ / ____/ /_/ / 
/___/_____/_/    \____/  
                         
```
`idp8` - `Infrared Data Protocol 8`

# Abstract
Assembly implementation of a `3 bit` `IR` data protocol for the `AVR ATtiny85`.

# Firmware Features
1. Variable `38 kHz` `IR` transmitter burst time (protocol independent).
2. Pulse delay encoding.
3. `TX` error detection.
4. High noise immunity.
5. Uses internal `8 MHz` `RC` oscillator.
6. Timer resolution of `100 μs`. 
7. Fully configurable and extensible.

# Warnings
The sample protocol provided is only intended to be used by one `TX/RX` pair.

> Note: The addition of multiple transmitters may cause data corruption or other unknown side effects! <br>

# Info
Included in the main source files is a `LED` demo. <br>
Four `LED's` can be controlled remotely using four tacticle push-buttons.

Schematics for the project are provided.

Folders:
* `/firmware` - `TX` and `RX` `AVR` firmware.
* `/schematics` - circuit schematics for `IR`, `TX` and `RX`.
* `/spec` - `IDP` protocol specification.

# Signature

```
+---------------------------------------+
|     .-.       .-.       .-.           |
|    /   \     /   \     /   \     +    |
|         \   /     \   /     \   /     |
|          "_"       "_"       "_"      |
|                                       |
|  _   _   _ _  _   _   ___   ___ _  _  |
| | | | | | | \| | /_\ | _ \ / __| || | |
| | |_| |_| | .` |/ _ \|   /_\__ \ __ | |
| |____\___/|_|\_/_/ \_\_|_(_)___/_||_| |
|                                       |
|                                       |
| Lunar RF Labs                         |
| https://lunar.sh                      |
|                                       |
| Research Laboratories                 |
| Copyright (C) 2022-2024               |
|                                       |
+---------------------------------------+
```
