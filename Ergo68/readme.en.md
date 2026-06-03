# Ergo68 Build Guide

![completed_assembly_Front](imgs/Completed_assembly_Front.jpg)
![completed_assembly_Back](imgs/Completed_assembly_Back.jpg)

Thank you for purchasing the Ergo68.

**Please read this build guide all the way through before you start the actual assembly.**

Please follow the steps in this guide when assembling the kit.
If you have any questions about the procedure, please refer to the Yushakobo [support page](https://yushakobo.zendesk.com/hc/ja) and feel free to contact us.

## Cautions

Assembly of this kit involves the use of sharp tools such as nippers and tools that can cause burns such as a soldering iron, so please work with sufficient care.
The kit contains small parts, so when storing them, please keep them out of the reach of children.
Debris produced during work — such as cut diode leads and pin header leads — can stick into your hands, so we recommend cleaning up as you work.
**Unplugging the TRS cable that connects the left and right halves while the keyboard is connected to a PC with a USB cable can cause failure.**
**Never unplug the cable connecting the left and right halves while the keyboard is connected to a PC.**

## 1. Check the parts included in the kit

First, please check that all parts included in the kit are present.
If any parts are missing, we apologize for the inconvenience — please contact us via the Yushakobo [inquiry form](https://yushakobo.zendesk.com/hc/ja/requests/new), selecting the category **"Missing parts or initial defects in purchased products"**.

|Name|Quantity|Image|
|---|---|---|
|PCB|2|![PCB](imgs/PCB.JPG)|
|Switch plate|2|![SW_Plate](imgs/SW_Plate.JPG)|
|Bottom plate|2|![Bottom_Plate](imgs/Bottom_Plate.JPG)|
|Cover plate|2|![Cover_Plate](imgs/Cover_Plate.JPG)|
|Pro Micro|2|![ProMicro](imgs/ProMicro.JPG)|
|Conthrough (12-pin)|4|![Conthrough](imgs/Conthrough.JPG)|
|Reset switch|2|![ResetSwitch](imgs/ResetSwitch.JPG)|
|TRRS jack|2|![TRRS](imgs/TRRS.JPG)|
|Screws (4mm)|28|![Screw](imgs/Screw.JPG)|
|Spacers (7mm)|14|![Spacer](imgs/Spacer7mm.JPG)|
|Spacers, male-female (4mm)|8|![Spacer](imgs/Spacer4mm.JPG)|
|Rubber feet (small)|4|![Cushion](imgs/Cushion.JPG)|
|Rubber feet (large)|4|![Cushion](imgs/Cushion.JPG)|

### 1-1. Optional parts (battery parts kit)

|Name|Quantity|Image|
|---|---|---|
|Coin cell battery holder|4|![Battery](imgs/Battery.JPG)|
|Conthrough|1|![Conthrough2mm](imgs/Conthrough2mm.JPG)|
|Schottky barrier diode|4|![Diode](imgs/Diode.JPG)|
|Chip capacitor|2|![Condenser](imgs/Condenser.JPG)|
|Slide switch|2|![SlideSW](imgs/SlideSW.JPG)|

### 1-2. Optional parts (AAA battery parts kit)

|Name|Quantity|Image|
|---|---|---|
|AAA battery holder|4|![BatteryAAA](imgs/BatteryAAA.JPG)|
|Conthrough|1|![Conthrough2mm](imgs/Conthrough2mm.JPG)|
|Schottky barrier diode|4|![Diode](imgs/Diode.JPG)|
|Chip capacitor|2|![Condenser](imgs/Condenser.JPG)|
|Slide switch|2|![SlideSW](imgs/SlideSW.JPG)|
|Cover plate (for AAA batteries)|2|![Cover_Plate_AAA](imgs/Cover_Plate_AAA.JPG)|
|Spacers, male-female (8mm)|8|![Spacer](imgs/XXXX.jpg)|
|Rubber feet (large)|4|![Cushion](imgs/Cushion.JPG)|

### 1-3. Optional parts (middle plates)

|Name|Quantity|Image|
|---|---|---|
|Middle plate (2mm)|2|![Middle2mm](imgs/Middle2mm.png)|
|Middle plate (5mm)|4|![Middle5mm](imgs/Middle5mm.png)|

## 2. Check the parts you need to prepare separately

Parts not included in the kit need to be prepared separately.
Please purchase them in advance and check that nothing is missing before starting assembly.

|Name|Quantity|Notes|
|---|---|---|
|Key switches|68|Purchase [here](https://shop.yushakobo.jp/collections/all-switches/cherry-mx-%E4%BA%92%E6%8F%9B-%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81)<br>Only Cherry MX-compatible switches are supported|
|Keycaps|68|Purchase [here](https://shop.yushakobo.jp/collections/keycaps/cherry-mx-%E4%BA%92%E6%8F%9B-%E3%82%AD%E3%83%BC%E3%82%AD%E3%83%A3%E3%83%83%E3%83%97)<br>Carefully check the key layout and keycap set before purchasing|
|TRS cable or TRRS cable|1|Purchase [here](https://shop.yushakobo.jp/products/trrs_cable)<br>For LPME-IO, only a TRRS cable can be used<br>TRS has 3 poles, TRRS has 4 poles|
|USB cable|1|Purchase [here](https://shop.yushakobo.jp/products/usb-cable-micro-b-0-8m)<br>Please prepare one matching the connector type of your microcontroller<br>The standard included Pro Micro requires a Micro B cable|

## Required tools

|Name|Notes|
|---|---|
|Soldering iron|Preferably one with temperature control|
|Solder wire|Around 0.6mm–0.8mm diameter|
|Screwdriver|For M2 screws (#0)|
|Nippers|Preferably ones with a fine tip|

**A [tool set](https://shop.yushakobo.jp/products/a9900to) is also available, so please consider it along with your parts.**

## Assembly steps

1. Solder the Pro Micro and Conthrough
1. Solder the reset switch and TRRS jack
1. Write the firmware and check operation
1. Break off the breakaway tabs on the left and right of the PCB
1. Attach the key switches to the switch plate
1. Screw down the spacers
1. Screw down the bottom plate
1. Screw down the cover plate
1. Attach the keycaps
1. Attach the rubber feet
1. Change the keymap
1. (Optional) Solder the battery parts kit

## 1. Solder the Pro Micro and Conthrough

**Check: Pay close attention to the orientation (front/back) of the Pro Micro.**
**If installed backwards, removing the Conthrough is very difficult.**

**Check: If you want wireless support, use a BLE Micro Pro instead of a Pro Micro — no soldering is required.**
**Refer instead to "EX1. Wireless support" later in this guide.**

### 1-1. Inserting the Conthrough

Insert the pin socket from the **back side** of the PCB.

![ProMicro-1](imgs/ProMicro-1.JPG)

When doing this, align the side where you can see the metal through the side of the Conthrough as shown in the photo below.
**Check: When using a Pro Micro, leave the top pin of the PCB empty — do not insert it.**

![ProMicro-2](imgs/ProMicro-2.JPG)

The Conthrough also has a top and bottom orientation.
The window where the metal is visible is offset toward one side; insert it so that the offset side is at the top.

![ProMicro-3](imgs/ProMicro-3.JPG)

### 1-2. Soldering the Pro Micro

Place the Pro Micro with the side where the components are visible facing up, and insert it into the Conthrough.

![ProMicro-4](imgs/ProMicro-4.JPG)

At this point, pay close attention to the orientation of the Pro Micro.
The chip components of the Pro Micro should be visible from the **front side** of the PCB.
Removing the solder from the Pro Micro later requires a great deal of effort, so **always check here** that there is no discrepancy with the photo above.

For soldering, feeding just 2–3mm of solder is sufficient.
Apply the soldering iron, wait 1–2 seconds, then feed solder.
Wait another 1–2 seconds, then remove the solder, and finally remove the soldering iron.
It should look like the images below.

## 2. Solder the reset switch and TRRS jack

**Point: The reset switch can also be used without soldering.**
**It is rarely used, so if you don't plan to rewrite the firmware frequently, you may skip soldering it.**
**Note that once the firmware is written, the reset switch is not needed for rewriting the keymap.**

On the back side of the PCB, on the opposite side from the Pro Micro, mount the reset switch and TRRS jack on the **back side** at the parts labeled `Reset` and `TRRS`, and solder them from the **front side**.

Left side ![ResetTRRS-Left](imgs/ResetTRRS-Left.JPG)
Right side ![ResetTRRS-Right](imgs/ResetTRRS-Right.JPG)

After soldering, you can cut the leads with nippers and reheat with the soldering iron so they don't scratch your desk.

![ResetTRRS](imgs/ResetTRRS.JPG)

## 3. Write the firmware and check operation

The Ergo68 uses qmk_firmware as its firmware.

The firmware is written using Remap's catalog feature.
**Check: For writing to BLE Micro Pro, refer to `EX1-5. Writing the firmware` at the end of this build guide.**

https://remap-keys.app/catalog/qIgO7rOq7GMRsGf6QhlY/firmware

When the firmware has been written, open Remap's configurator screen.

https://remap-keys.app/configure

Click FLASH.

![Remap-1](imgs/Remap-1.png)

For a normal Pro Micro select "caterina"; for Elite-C select "dfu", then click FLASH.
* Writing using "dfu" may require separate work with a tool called Zadig.

![Remap-2](imgs/Remap-2.png)

As shown below, confirm that "Arduino Micro" or similar appears in the small window.
If it does not appear, try changing the cable or the port you are connecting to.

![Remap-6](imgs/Remap-6.png)

When you press the reset switch, there will be a brief sound as if the USB device has been disconnected. Confirm that the Arduino Micro port number in the small window has changed, and quickly click "Connect".
(In this guide's example, COM17 changes to COM18.)
If the port number does not change, try pressing reset twice quickly.

![Remap-7](imgs/Remap-7.png)

When firmware writing is complete, "successfully" will be shown at the end of the message, as in the figure below.
**Check: When using something other than a normal Pro Micro (like Elite-C), it may fail.**
**For Elite-C and similar, change the Bootloader to dfu and follow Remap's instructions to switch the dfu USB mode.**

![Remap-8](imgs/Remap-8.png)

First, check that all the LEDs light up.

![Remap-9](imgs/Remap-9.JPG)
![Remap-10](imgs/Remap-10.JPG)
**Point: The upper LEDs on the left and right are indicators.**
**Left side: CapsLock, NumLock, ScreenLock.**
**Right side: layer state.**
**It is normal for these indicators to be off even when connected to the PC.**

Once Remap recognizes it correctly, open test mode and touch the metal part of the switch socket with tweezers to check continuity.

![Remap-3](imgs/Remap-3.png)
![Remap-4](imgs/Remap-4.JPG)

If everything is working, all the keys will turn blue as shown below.
![Remap-5](imgs/Remap-5.png)

## 4. Break off the breakaway tabs on the left and right of the PCB

Break off the breakaway tabs attached to the left and right of the PCB.

![PCB-1](imgs/PCB-1.JPG)

**Check: Applying too much force across the whole PCB while breaking can cause the switch sockets to come off.**
**If it is hard to break, score it with a knife or cut it with nippers.**

![PCB-2](imgs/PCB-2.JPG)

## 5. Attach the key switches to the switch plate

Attach the key switches to the switch plate.
First, fit switches into the four corners of the switch plate.

![SW-1](imgs/SW-1.JPG)

**Check: Only the switches at the thumb cluster have a different orientation.**
**Compare with the orientation of the switch sockets on the PCB and fit them into the switch plate in the correct orientation.**

![SW-2](imgs/SW-2.JPG)

**Check: Make sure the switches are firmly seated in the switch plate.**

![SW-3](imgs/SW-3.JPG)

**Check: If installing a middle plate, sandwich the middle plate (2mm) between the PCB and switch plate.**
Align the switch plate with the PCB and fit the switch terminals into the PCB's switch sockets.
**Check: Before inserting into the switch sockets, double-check that the switch orientation is correct and that the pins are not bent.**

![SW-4](imgs/SW-4.JPG)

**Check: Push the switches all the way in.**

![SW-5](imgs/SW-5.JPG)

Install all the switches.
**Check: Be careful of switch orientation.**
**Point: Testing once more with Remap at this point makes it more reliable.**

![SW-6](imgs/SW-6.JPG)

## 6. Screw down the spacers

Attach the spacers (7mm) to the switch plate.
Place a spacer over a screw hole on the back of the switch plate, hold it in place with your finger, and screw it down from the front side of the switch plate.
**Point: If installing a middle plate, stacking the 5mm plate underneath keeps the spacer from spinning and makes it easier to tighten.**
**Point: If it's hard to hold the spacer with your finger, lightly fixing it with masking tape can save you frustration.**

![Screw-1](imgs/Screw-1.JPG)
![Screw-2](imgs/Screw-2.JPG)
![Screw-3](imgs/Screw-3.JPG)
![Screw-4](imgs/Screw-4.JPG)

## 7. Screw down the bottom plate

**Point: If adding wireless support, install the battery parts first by referring to EX1. Wireless support before attaching the bottom plate.**

Place the bottom plate on top and screw it down at 3 points on the lower half.

![Screw-5](imgs/Screw-5.JPG)

Then, screw in the male-female spacers (4mm) at the 4 points on the upper half by hand.

![Screw-6](imgs/Screw-6.JPG)

## 8. Screw down the cover plate

Place the cover plate on top of the male-female spacers (4mm) on the upper half of the bottom plate and screw it down.
**Point: When using a Pro Micro with Conthrough, the Conthrough can come loose from plugging and unplugging the USB cable, causing keys to stop working.**
**To prevent this, a known technique is to attach cushion rubber between the Pro Micro and the cover plate to keep it from coming loose.**
**If you plan to plug/unplug the USB cable frequently, consider it.**

![Screw-7](imgs/Screw-7.JPG)

## 9. Attach the keycaps

Attach the keycaps you prepared.

## 10. Attach the rubber feet

Attach rubber feet at 8 locations total — left and right — on the bottom plate and cover plate.
Attach the taller rubber feet on the cover plate side.
For attachment positions, refer to the round markings printed on the bottom plate and cover plate.

## 11. Change the keymap

Change the keymap to suit your usage.
Remap is convenient for changing the keymap.

https://remap-keys.app/configure

For how to use Remap, refer to the following site.

https://salicylic-acid3.hatenablog.com/entry/remap-manual

## EX1. Wireless support

By using a BLE Micro Pro instead of a Pro Micro, you can make a wireless connection via Bluetooth.
Even just swapping in the BLE Micro Pro allows USB power via a mobile battery, etc., but using the BLE Micro Pro battery board parts allows you to embed a coin cell battery (CR1632).
In addition to BLE Micro Pro, you can use [LPME-IO](https://shop.yushakobo.jp/products/lpme-io2a) for partial wireless — only the connection between the left and right halves — using a **4-pole** TRRS cable.
However, for both fully wireless (using two BLE Micro Pros) and partially wireless (BLE Micro Pro + LPME-IO), only the left keyboard can connect to the PC.
The right keyboard only relays key presses to the left keyboard.
Also note that with a BLE Micro Pro wireless connection, the LEDs only light up when on USB power.

### EX1-1. Installing the BLE Micro Pro

**Check: No soldering is required for the BLE Micro Pro when using Conthrough.**
**The same applies to LPME-IO, but LPME-IO requires jumpers on the microcontroller board.**

If you use a 13-pin Conthrough (sold separately), use it as-is. (Recommended)
If you use the included 12-pin Conthrough with the BLE Micro Pro, install it as shown in the photos below. (Same for LPME-IO.)
The BLE Micro Pro has battery pins at the upper right (with the USB connector at the top), so install the Conthrough offset by 1 pin on the right side only.
The orientation of the Conthrough should be matched, just like with the Pro Micro.

Left side ![BMP-1](imgs/BMP-1.JPG)
Right side ![BMP-2](imgs/BMP-2.JPG)
**\*The examples in these photos use 12-pin Conthrough.**
**With 13-pin Conthrough, no offset is needed.**

Left side BMP installation example ![BMP-3](imgs/BMP-3.JPG)
Right side BMP installation example ![BMP-4](imgs/BMP-4.JPG)

LPME-IO jumper area ![LPME-IO-1](imgs/LPME-IO-1.png)
The LPME-IO jumper area is slightly raised and can short against the socket, so insulating it with tape is a safe bet.
![LPME-IO-2](imgs/LPME-IO-2.png)
LPME-IO installation example ![LPME-IO-3](imgs/LPME-IO-3.png)

### EX1-2. Soldering the battery parts

The battery parts are soldered to the bottom plate.
Before soldering, it is helpful to attach masking tape to identify left and right so you don't mix them up.
**Check: When using LPME-IO, soldering of the battery parts on the LPME-IO side (right side) is not necessary.**

![BMP-5](imgs/BMP-5.JPG)
![BMP-6](imgs/BMP-6.JPG)

First, attach the capacitor and Schottky barrier diode on the front side of the bottom plate (the side with masking tape, which will face the PCB).
These two parts are surface-mount components (parts attached to the surface of the board), so they require a bit of technique.

First, put a small amount of "preliminary solder" on the board.

![BMP-7](imgs/BMP-7.JPG)

Then, holding the diode or capacitor with tweezers, melt the preliminary solder with the soldering iron while placing the diode or capacitor on the board.

![BMP-8](imgs/BMP-8.JPG)

Once the preliminary solder melts and tacks the part in place, solder the other lead of the diode as well.
If the solder becomes pointy from being heated too long, adding flux tends to help.

![BMP-9](imgs/BMP-9.JPG)

Next, solder the slide switch to the back side of the bottom plate (the side without masking tape, which will be the bottom).
Insert the slide switch with the knob facing downward into the hole, and tack it with masking tape.

![BMP-10](imgs/BMP-10.JPG)

Flip it over, cut the slide switch leads close to the board, and solder them.

![BMP-11](imgs/BMP-11.JPG)
![BMP-12](imgs/BMP-12.JPG)
![BMP-13](imgs/BMP-13.JPG)

Finally, solder the battery holder to the back side of the bottom plate (the side without masking tape, which will be the bottom).
The coin cell battery holder has an orientation; refer to the photo below.

![BMP-14](imgs/BMP-14.JPG)

When flipping it over to solder, hold the holder down with masking tape or similar so it doesn't lift up, and solder it.

![BMP-16](imgs/BMP-16.JPG)

The AAA battery holder is the same.
The AAA battery holder has + and − poles on the left and right, so be careful of orientation.

![BMP-15](imgs/BMP-15.JPG)

Flip it over, cut the leads close, and solder them.
If parts lift up, holding them with masking tape makes it easier.

![BMP-17](imgs/BMP-17.JPG)

### EX1-3. Preparing the 2-pin Conthrough

The bottom plate where the battery is mounted and the PCB where the microcontroller is mounted are connected by a 2mm 2-pin Conthrough.
Conthrough can easily be cut with nippers or a knife, so cut off 2 pins from a 12-pin Conthrough.
Cutting directly above a hole in the Conthrough makes it very easy.

![BMP-18](imgs/BMP-18.JPG)
![BMP-19](imgs/BMP-19.JPG)

Insert the cut 2-pin Conthrough into the connection pins on the PCB.
They are located near the BLE Micro Pro.
Orientation doesn't matter.

![BMP-20](imgs/BMP-20.JPG)

### EX1-4. Connecting the bottom plate

Carefully place the bottom plate on, being careful not to bend the 2-pin Conthrough.

![BMP-21](imgs/BMP-21.JPG)

For the coin cell battery case, the rest of the assembly steps are the same as for the Pro Micro.
When using the AAA battery case, combine the male-female spacers (4mm) and male-female spacers (7mm).
First, screw the 7mm spacers into the bottom plate, then screw the 4mm spacers on top of those.
On top of that, use the cover plate that has holes for AAA batteries.
Use the larger dedicated rubber feet as well.

### EX1-5. Writing the firmware

Please write the firmware from the BLE Micro Pro Web Configurator below.

https://sekigon-gonnoc.github.io/BLE-Micro-Pro-WebConfigurator/

Run the steps of the BLE Micro Pro Web Configurator in order from top to bottom.
After running them in order, use the "Write keyboard-specific settings" button and select "Ergo68" to write.

![BMP-22](imgs/BMP-22.png)
![BMP-23](imgs/BMP-23.png)

After writing the settings, apply the default keymap from Remap or from the BLE Micro Pro repository.

![BMP-22](imgs/BMP-24.png)
![BMP-23](imgs/BMP-25.png)

Alternatively, download the default Ergo68 keymap for BLE Micro Pro from GitHub and drag-and-drop it onto the BLE Micro Pro removable media.
https://github.com/sekigon-gonnoc/BLE-Micro-Pro/blob/master/AboutDefaultFirmware/keyboards/ergo68/KEYMAP.JSN

After writing, the procedure is the same as "3. Soldering the reset switch".

**Point: For BLE Micro Pro-specific issues such as unstable Bluetooth connections or being unable to rewrite the keymap, check the FAQ [here](https://sekigon-gonnoc.github.io/BLE-Micro-Pro/#/FAQ).**
