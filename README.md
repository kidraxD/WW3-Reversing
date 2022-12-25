# WW3-Reversing
My personal reversing results from the game World War 3
## Unreal Engine

Verion 4.21

## Offsets

UWorld -> **0x4977B18** | 48 89 05 38 F1 9E 02

GObjects -> **0x43A9D04** | find it in processevent

GNames -> **0x4883638** | 48 89 1D 90 61 74 03

ProcessEvent -> **0x12C7560** | 40 55 56 57 41 54 41 55 41 56 41 57 48 81 EC F0 00 00 00 48 8D 6C 24 30

GetBoneMatrix -> **0x1EB5BF0** | 48 8B C4 48 89 58 10 55 56 57 41 54 41 55 41 56 41 57 48 8D 68 A1 48 81 EC F0 00 00 00
