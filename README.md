#CAD files

Here are all the CAD files I've created for systems through out the lab. Where possible I'll also include assembly and usage photos.

TO ADD
+	X88 : table + optics + chamber
+	X88 + twins : oven + oven mount
+	uCavity : chamber + optics
+	Doubling cavity
+	Doubling cavity v2
+	twins: cavity mounts - stage + flexure
+	Reference cavities
+	rack paneling 
+	Pump housings

## twins / Experiment flange

![XFlange](twins/Experiment\ flange/HOATrap.png)

The experiment is designed around a 100-pin ceramic-pin-grid-array (CPGA) chip carrier. This is a standard that our group has used for years, and trap-fabrication groups such as Sandia national labs have standardized between many groups. 

###Components

+	A custom 6in base-flange from accuglass inc, routes all 100-pin's out via two Dsub-50 connectors. These connectors where chosen for their high pin density while still having a small amount of feed-through capacitance (~10pF). The flange also has a centered 1 1/3' CF port, allowing the placement of a viewport for optical access through the chip, or to house an oven if optical access is not required. *** For future versions, note that the flange has room for an additional 2 1 1/3' CF ports in the line between the DB connectors. We've considered adding these on future setups for additional wiring outlets, or to have welded 1 1/3' nipples welded on at 30-45deg for additional optical access. 

+	1/8in thick Rogers 4350 PCB 2-sided with soft gold traces: The trap socket consists of this PCB along with mill–max 0461-3-15-15-21-27-04-0 pins, After the first assembly of the X88 system we found that mating the trap into the socket often bent these pins and a lot of care was needed to insert the trap without breaking off any pins. After that we made a top-support piece made from macor to prevent the pins from moving during trap insertion, care is still needed to make sure each CPGA-pin enters the mating pin but there is no longer any danger of damaging the socket. 

+	Macor support: on top of the rogers CPGA a macor support is placed around the mill-max pins. The macor support has 3 tapped-holes for mounting an adapter to a smar-act 3-axis stage and holds a right-angled mirror which both allows for additional optical access and, primarily, serves as an oven block preventing Sr from being deposited on the majority of the trap surface. 
[insert image]

+	wiring + support: electrical connections are made to the db connectors via 18awg silver platted wire. We buy kapton coated from accuglass even though we strip the kapton off before assembly. This was the only supplier we could get a small amount of silver platted copper wire from. The silver platting was desired for its reduced RF resistance. This was also the reason for the higher-gauge wire. We typically see RF resistances of 1-3OHms at 50MHz, including DB-feedthrough, wound air-inductor, CPGA-pins + wiring, + trap wire-bonds and connections. The other advantage of the low guage wire is the pcb is completely rigidly supported by the 100x ~1.2in long wires. Connections to the flange db-connectors are made via crimped gold-plated db-pins which are housed in 2 macor db-connectors both from accuglass. Connections to the PCB are made with Sn-Ag solder. 

The original mount included 4 aluminum supporting feet which braced the PCB around the CPGA-insertion. But 
