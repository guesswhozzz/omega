# 021011 EZ-FLASH OMEGA Kernel

## Less loop more power 

021011 lite version of EZ-FLASH OMEGA Kernel based on [original EZ-FLASH repo](https://github.com/ez-flash/omega-kernel) 


### How to build 

    1.We use devkitARM_r47, you can use the current version or newer.
    2.Set the following environment variables in system, or modify the value in build.bat, based on your installation path
 
        PATH,DEVKITARM,DEVKITPRO,LIBGBA

    3.Double click on build.bat under winodws. If it goes well, you will get ezkernel.gba
    4.Rename the ezkernel.gba to ezkernel.bin, that is the omega kernel upgrade file
