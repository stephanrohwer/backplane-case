# stackable HDD backplane case with small footprint *under development*

![single rack without drives](/assets/images/single-rack-without.png)

![single rack with some drives](/assets/images/single-rack-with.png)

![hdd with slider](/assets/images/hdd-with-slider.png)

![hdd sliding in](/assets/images/hdd-sliding-in.png)

## used components
- 1x Hard Disk Backplane Board - ProLiant DL380p / DL380e Gen8 - 647407-001
- 1x SAS controller with hba mode
- 1x Powersupply (without staggered spinup twice as high)

## powersupply connectors
![info for powersupply](/assets/images/powersupply.png)
I used a variable power supply to check current consumption on spinup.
On my chia farm I used 24 drives with two backplanes and on spinup current is at 26A max, but on regular farming at 13A.
Staggered spinup could be do the job to reduce current consumption, but I haven't tested it.

![assembled connector left](/assets/images/power-connector-left.png)

![assembled connector right](/assets/images/power-connector-right.png)

## sas connector

Both connectors are of type SFF-8087

I only use port 1

![sas connector](/assets/images/sas-connectors-sff-8087.png)

## stl files

[Download v0.0](/stl/backplane-case-v0.0.7z)

### wall
![wall](/stl/v0.0/wall-v0.0.1.png)

### mount
![mount](/stl/v0.0/mount-v0.0.1.png)

### bridges
![bridge](/stl/v0.0/bridge-v0.0.1.png)

### slider for drives
![slider](/stl/v0.0/slider-v0.0.1.png)

### fan mount
*under development*

## needed parts
- 5x wall
- 5x mount
- 8x bridges
- 24x sliders (2x for each drive)
- ?x fan mount
- 20x [ruthex M3](https://www.ruthex.de/collections/gewindeeinsatze/products/ruthex-gewindeeinsatz-m3-100-stuck-rx-m3x5-7-messing-gewindebuchsen)
- 72x hdd drive screws flat head unc #6-32
- 10x flat-head m3 for mount
- 10x m3 for bridge
