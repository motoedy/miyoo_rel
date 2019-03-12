# Linux OS for Miyoo/Bittboy handheld
![Alt text](miyoo.bmp)  
(Designed by win2next)

## Patch (20190312):
  1. gmu_20190312.zip  
    + A: add music into play list  
    + START: change tab page  
    + SELECT -> START: quit  
    + R menu: turn screen off  
    + R (START + A): turn screen on  
  2. gambatte_sdl_20190312.zip  
    + Remove hotkey for both Quick Save/Load  
    + Remap A and B button  
  
## Patch (20190311):
  1. gambatte_sdl_20190311.zip  
    + Porting from RS97 source  
    + B: Quick Save  
    + TB: Quick Load  
  
## Patch (20190304):
  1. openbor_20190304.zip  
    + Fix wrong color mapping  
  
## Patch (20190303):
  1. sorr_20190303.zip  
    + Fix hang issue in SORR game  
  2. asciiportal_20190303.zip  
    + Porting from RS97 source  
  3. digger_20190303.zip  
    + Porting from RS97 source  
  4. mrdrillux_20190303.zip  
    + Porting from RS97 source  
  5. openbor_20190303.zip  
    + Porting from RS97 source  
  6. kernel_20190303.zip  
    + Fix invalid GPIO setting (support hardware fix for ghost key problem)  
  7. miyoo_spi_hwmod_1bit_ghostkey_20190303.bin  
    + Only work on hardware fix for ghost key problem  
  8. miyoo_spi_hwmod_4bit_ghostkey_20190303.bin  
    + Only work on hardware fix for ghost key problem  
  
## Patch (20190227):
  1. miyoo_spi_hwmod_1bit_earphone_20190227.bin  
    + Fix earphone issue  
  2. miyoo_spi_hwmod_4bit_earphone_20190227.bin  
    + Fix earphone issue  
  
## Patch (20190226):
  1. fceux_20190226.zip  
    + Improve user experience for both LoadState and SaveState  
  
## Patch (20190224):
  1. miyoo_spi_hwmod_1bit_ghostkey_20190224.bin  
    + Ignore START when press LEFT + DOWN + B  
  2. miyoo_spi_hwmod_4bit_ghostkey_20190224.bin  
    + Ignore START when press LEFT + DOWN + B  
  3. pcsx_rearmed_20190224.zip  
    + Support vibration feature  
  4. miyoo_spi_hwmod_1bit_vibration_20190224.bin  
    + Support vibration feature  
  5. miyoo_spi_hwmod_4bit_vibration_20190224.bin  
    + Support vibration feature  
  
## Patch (20190223):
  1. cdogs_20190223.zip  
    + Porting from GCW0 source  
  2. gmenu2x_20190223.zip  
    + Repack more icons in Default folder  
  
## Patch (20190222):
  1. ccdoom_20190222.zip  
    + Support fullscreen render (parameter used in GMenu2X: "-iwad $1")  
  2. wolf3d_20190222.zip  
    + Porting from RS97 source  
  
## Patch (20190221):
  1. miyoo_spi_hwmod_1bit_l1r1l2r2_20190221.bin:  
    + Support L1, R1, L2 and R2 keys (press at the same time: Start + B/A/TB/TA)  
  2. miyoo_spi_hwmod_4bit_l1r1l2r2_20190221.bin:  
    + Support L1, R1, L2 and R2 keys (press at the same time: Start + B/A/TB/TA)  
  
## Patch (20190220):
  1. gpsp_20190220.zip  
    + Add border image (border.png, border_sp.png)  
  2. miyoo_spi_hwmod_1bit_ghostkey_20190220.bin  
    + Alleviate ghost key issue for SDCard 1Bit handheld (change scanline from x to y)  
  3. miyoo_spi_hwmod_4bit_ghostkey_20190220.bin  
    + Alleviate ghost key issue for SDCard 4Bit handheld (change scanline from x to y)  
  
## Patch (20190219):
  1. gngeo_20190219.zip  
    + Porting from RS97 source  
  2. gmenu2x_20190219.zip  
    + Include more themes and pictures  
  3. ohboy_20190219.zip  
    + Add palettes and borders  
  
## Patch (20190218):
  1. kernel_20190218.zip  
    + Fix black screen issue when exit emulator  
  2. pcsx_rearmed_20190218.zip  
    a. Screen center for game with resolution 256x240  
    b. Fix crash issue when exit emulator  
  3. gpsp_20190218.zip  
    + Fix Select key issue  
  
## Patch (20190217):
  1. kernel_20190217.zip  
    + Fix compatible issue with pcsx rearmed emulator  
  2. pcsx_rearmed_20190217.zip  
    + Porting from notaz Github (parameter used in GMenu2X: "-cdfile $1")  
  3. gpsp_20190217.zip  
    + Fix crash issue when show setting menu  
  
## Patch (20190216):
  1. kernel_20190216.zip  
    + Fix improper init code for lcd screen (issue: need reboot to enter GMenu2X)  
  2. miyoo_spi_hwmod_1bit_ghostkey_20190216.bin (flash via usb)  
    + Fix ghost key issue for SDCard 1Bit handheld (report nothing when the number of pressed key >= 3)  
  3. miyoo_spi_hwmod_4bit_ghostkey_20190216.bin (flash via usb)  
    + Fix ghost key issue for SDCard 4Bit handheld (report nothing when the number of pressed key >= 3)  
 
## Patch (20190214):
  1. Framebuffer driver: kernel_20190214.zip(replace original r61520fb.ko in kernel folder)  
    a. Support double buffer  
    b. Reduce screen flickering  
 
## V1.0 (20190203):
  1. First release  
  2. Framebuffer driver does not support double buffer  
  3. All of emulators/games/apps/gmenu2x are built without enabling double buffer  
  4. Included apps: commander  
  5. Included games: chocolate doom, sdlpal v1, sdlpal v2, sorr  
  6. Included emulators: fceux, gpsp, ohboy, picodrive, sms, snes9x4d, temper  
 
## Stock ROM:
  1. miyoo_stock_v1.bin is for v1 miyoo/bittboy handheld  
  2. miyoo_stock_v2.bin is for v2 miyoo/bittboy handheld  
  
## Hotkey:
  1. L1: Start + B  
  2. R1: Start + A  
  3. L2: Start + TB  
  4. R2: Start + TA  
  5. Volume: Select + A/B  
  6. Backlight: Select + TA/TB  
 
## Poweroff:
  + Please run poweroff icon in GMenu2X and then switch off power button when black screen 
  + If you switch off power button directly, SDCard might corrupt due to sync issue
 
## Known issues:
  1. Ghost keys when press more than 3 keys  
  2. Need to double click DOWN key when start the game of sdlpal_v1/sdlpal_v2  
  3. Take about 5 seconds back to 60fps in sms emulator  
