# Kernel64Patcher
A 64-bit kernel patcher based on xerub's patchfinder64.

## Changes
iOS 13.2+ fat macho kernels such as those found in t8010 and t8011 now remain fat after patching.

## Compiling
```
gcc Kernel64Patcher.c -o Kernel64Patcher
```
## Usage
```
./Kernel64Patcher kcache.raw kcache.patched -a
```
## Credits/Thanks
* xerub for patchfinder64
* iH8sn0w for code
