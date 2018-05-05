TWRP device configuration for LeEco Le Max 3
==============

To compile android-8.1 based TWRP
==============

export ALLOW_MISSING_DEPENDENCIES=true

. build/envsetup.sh && lunch omni_x10-eng

mka adbd recoveryimage
