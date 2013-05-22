android_kernel_alcatel_cocktail
==================================

Alcatel OT-995/996 (cocktail) kernel tree (GB 2.6.35 - 2012-11-07)


$HOME/android/kernel <--- kernel files

$HOME/android/arm-eabi-4.4.3a <--- this toolchain



cd ~/android/kernel/

export ARCH=arm

export CROSS_COMPILE=arm-eabi-

export PATH=$HOME/android/arm-eabi-4.4.3a/bin:$PATH

export KERNEL_DIR=`pwd`

make msm7630-cocktail-perf_defconfig

make -j5
