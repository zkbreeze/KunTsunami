KunTsunami
===
Particle-based rendering library for Tsunami data created by Kun Zhao.

## Requirements
* [KVS](https://github.com/naohisas/KVS) 
* [CMake](http://www.cmake.org/)

## Settings

### Windows
|Variable|Value|
|:-------|:----|
|KUN_SHADER_DIR |C:*\KunPBR\lib\Shader\ |

### Linux
```
export KUN_SHADER_DIR=*/KunPBR/lib/Shader/
```

## Build
```
cd Bin
cmake ..
make
```

## Usage
```
./run_*/run_*.sh
use -minx [coord] ** to clip the range
```