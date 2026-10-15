The XBox 360 motherboard has gone through several changes over the
years. These changes often reduced die sizes of various chips (CPU
(Xenon), GPU (Xenos), [eDRAM](http://en.wikipedia.org/wiki/EDRAM),
etc.), added new features (HDMI, etc.) and patched the SMC/JTAG exploit.
This pages lists off all known motherboard revisions, their changes as
well as links to their respective pages.

<!--- Not an issue with GitHub PRS - halotroop2288
'''NOTE TO MAINTAINERS: ''' This page is often ripped apart by spam
bots! Please check and revert any unwanted changes regularly!
--->

## [Xenon](../Xenon_(Motherboard).md) 

The original Xbox 360 configuration used in the initial Premium and Core machines released in the end of November 2005. 
These are also known as the RRoD (Red Ring of Death) machines because the majority of these machines are affected with defective GPUs.

  - Consoles : Core, Pro/Premium 20 GB
  - 90 nm IBM CPU (Waternoose DD2)
  - Y1 GPU
    - 90 nm ATI GPU die (Xenos C1)
    - 90 nm on-chip [eDRAM](http://en.wikipedia.org/wiki/EDRAM) (Edifis)
  - Low profile GPU cooler (most of the time)
  - Standard CPU cooler
  - 203 Watt output power supply (16.5 A)
  - Shipping with Hitachi46-78, Samsung ms25or ms28, or BenQ DVD-Drive. Can
    also come with Lite-On drive if it was refurbished.
  - Highly unlikely to have glue around the CPU but it IS possible.

## [Zephyr](./Zephyr.md) 

Zephyr was the first revision with HDMI connector. It was introduced with the Xbox 360 Elite in May 2007.
In July 2007, Xbox 360 Premium machines began appearing with the Zephyr motherboard.

  - Consoles: Arcade, Pro/Premium 20GB, Elite 120GB and Halo 3 Console
  - 90 nm IBM XCPU
  - Y2 GPU
    - 90 nm ATI Xenos GPU die (Xenos C2, smaller than C1)
    - 90 nm [eDRAM](http://en.wikipedia.org/wiki/EDRAM) (Edifis)
  - 203 Watt PSU (16.5 A)
  - **HDMI** video output
  - Updated motherboard layout
  - Glue around the CPU in some cases
  - 3 pin fan connector
  - New **Extended GPU** heat sink with a heat pipe
  - New Elite model includes 120 GB hard drive
  - Shipping with Hitachi 78 or 79 and **BenQ** DVD-Drive. May also have
    Lite-On if it was refurbished.

## [Falcon](./Falcon.md)
All Xbox 360 Premium machines and Arcade machines made in August 2007 introduced the new 65 nm CPU accompanied with a new cooler and still 90 nm GPU with the Zephyr cooler.
The motherboard is based on Zephyr and requires fewer components (some capacitors and coils removed) for the new 65 nm CPU, resulting in lower costs.

  - Consoles: Arcade, Pro/Premium 20GB & 60GB, Elite 120GB
  - **65 nm** IBM CPU (Loki)
  - Rhea GPU; 90 nm ATI GPU die (Xenos C2) with 90 nm on-chip
    [eDRAM](http://en.wikipedia.org/wiki/EDRAM) (Styx-90)
  - HDMI Video Output
  - **175 Watt** PSU (2V rated for 14.2A, new connector)
  - New CPU Heat sink + the GPU heat sink with heat pipe
  - Fewer voltage regulators, capacitors and inductors
  - Bigger and enhanced **CPU cooler**
  - RAM removed from bottom of mainboard on later models
  - 3 pin fan connector
  - Shipping with Hitachi 79, BenQ and new Lite-On 7XXX series DVD-Drive

### [Opus](Falcon.md#opus)

This is an intermediate motherboard with 65 nm CPU and 90 nm GPU, new
coolers, but no HDMI. It was used in Xenon chassis for repairs and RRoD affected machines.
Started to appear at the end of July 2008 in non-HDMI machines coming back from repair.
It's just a Falcon without a custom A/V (HDMI) port so that it fits into a Xenon chassis and case.

  - Consoles: Core, Pro/Premium 20GB
  - Falcon based board
  - 65 nm IBM CPU (Loki)
  - Rhea GPU; 90 nm ATI GPU die (Xenos C2) with 90 nm on-chip
    [eDRAM](http://en.wikipedia.org/wiki/EDRAM) (Styx-90)
  - **No HDMI** Video Output
  - 175 Watt PSU (2V rated for 14.2A, new connector)
  - Updated Heat sinks
      - Falcon CPU cooler
      - Zephyr GPU cooler
  - 3 pin fan connector
  - Shipping with Hitachi, Samsung, BenQ and Lite-On 7XXX DVD-Drive
  - **Opus only available from Xenon being repaired by MS**.
  - Very Rare

## [Jasper](./Jasper.md)

Jasper introduced the 65nm GPU to reduce power usage and cost further.
The new power supply is rated for 150 Watt, down from 175 Watt on the
Falcon. The Amperage on the 12V rail is down to 12.1A (12.1A x 12V = 145.2W).

The on-board flash for motherboards that came with Arcade models has also increased to allow the new NXE (New Xbox
Experience) dashboard update to reside internally, instead of requiring an external memory unit or the hard drive.

  - Consoles: Arcade 256 MB & 512 MB, Pro/Premium 60 GB, Elite 120 GB &
    250 GB and Resident Evil 5 console
  - 65 nm IBM CPU (Loki)
  - **65nm** ATI GPU with 80nm on-chip
    [eDRAM](http://en.wikipedia.org/wiki/EDRAM)
  - **150 Watt** PSU (12V rated for 12.1A, new connector)
  - Arcade Edition Larger Flash **256MB** or 512MB Hynix HY27UF082G2B
    on-board flash, up from 16MB HY27US08281A flash, to accommodate the
    NXE update.
  - New Southbridge chipset
  - Ram removed from bottom of mainboard
  - New style CPU Heat sink + the GPU heat sink with heat pipe
  - 3 pin fan connector.
  - New Warranty Sticker.
  - Shipping with LiteOn 7XXX/8XXX/V2/9XXX DVD-Drivers.
  - Least likely to red ring of death (RRoD) due to the less heat being
    outputted by the chips

### Tonasket

Same as Jasper, minor changes.

  - Consoles: Arcade 512 MB, Elite 120 GB & 250 GB, Modern Warfare 2
    editions, and Final Fantasy 13 editions.
  - 65nm [eDRAM](http://en.wikipedia.org/wiki/EDRAM) (?)
  - New [Southbridge](../Southbridge.md) (PSB) chipset
  - Arcade Editions only use **512 MB** unlike Jasper
  - Shipping with Lite-On 8XXXV2/9XXX DVD-Drivers.
  - JTAG Hack / SMC patched on CB level
  - Xenon-style GPU heat sink with Falcon style CPU heat sink
  - Special edition consoles: Modern Warfare 2 Consoles
  - Last of the original style 360 systems

## [Trinity](./Trinity.md) \[Xbox 360 S\]

  - Consoles: 4 GB (Matte black), 250 GB (Glossy black), Halo Reach edition, and Gears of War edition
  - Unified CPU, GPU, and eDRAM on one chip called **Vejle**.
    - CPU and GPU are on one combined die made on the 45 nm process.
    - eDRAM is a seperate die, and it's the same Styx-65 design used on the [Tonasket](Jasper.md#Tonasket)'s Kronos.
  - 16 MB NAND
  - 135 Watt PSU
  - 802.11n Wi-Fi integrated
  - No more external Memory Unit ports
  - Built-in Kinect port
  - HDD is redesigned to connect to the console directly with SATA, unlike the previous fat model.
  - Smaller form factor than previous model
  - On 4 GB consoles, there is a 4 GB Memory Unit on small daughter board
  - No more RROD; major errors will show an RDOD (Red Dot of Death) on the center LED rather than the player LEDs.

## Corona \[Xbox 360 S\]

Referenced in 20353 xbdm.dll, nothing known right now, possibly the
newer cheaper XDKs?

Information on this board so far:

  - Many say that it is a Trinity Revision (Trinity v2)
  - Console: Forza 4 250 GB (This board was found in a Forza 4 bundle)
  - Manufacture Date: 8-17-2011
  - No HANA Chip, it's integrated into the Southbridge
  - 115 W PSU
  - CPU: 45 nm Combined Chip (Basicaly the CPU and GPU are combined)
  - HDMI Enabled

The interesting thing is that it seems that Microsoft knew about the
Reset Glitch Hack, so they removed the HANA Chip. So it seems Microsoft
found the exploit days before GliGli brought it out for the public.

Corona Sources:
[Source 1](http://en.wikipedia.org/wiki/Xbox_360_technical_specifications#List_of_revisions)
[Source 2](https://web.archive.org/web/20160515071713/http://www.xboxhacker.org/index.php?topic=17143.0)

[Category: Hardware](../../index.md)
