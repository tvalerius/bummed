Title: Colony lysis procedure for riboprobe synthesis  
Author: M. Todd Valerius  
Date created: 2002-10-10
Date updated: 2009-02-17


# Colony lysis procedure for riboprobe synthesis #

[Download PDF](https://sites.google.com/site/valeriuslabprotocols/pro/Colony-Lysis.pdf?attredirects=0&d=1)

## Description ##
This protocol starts with a single bacterial colony and makes PCR generated template for *in vitro* transcription reactions. The PCR reaction can also be used on plasmid DNA at 5ng/ul to generate probe template directly instead of digestion, etc.

## Method ##
###Colony picking and lysis

*Colony Lysis Buffer*

* 1% Triton X-100
* 20mM Tris pH 8.0
* 2mM EDTA pH 8.0 

Pick 6 single colonies (leave some on the plate for growth later) and place each into 25ul of Colony Lysis Buffer in a 96well PCR plate. The best technique is to smear the cells onto the side of the well. Seal plate with sealing mat or a foil sealer. (NOTE: When using clone specific primers you can pick a single colony since the primers will serve as the quality control). I use regular sterile pipet tips for picking colonies.

Heat in the PCR machine at 95C for 10min, cool on ice. The DNA is now ready for PCR.

###PCR Reaction 
To generate probe template, perform PCR with *clone* specific primers (preferred) or *promoter* specific primers (T3, T7, SP6), typically using a 25ul volume PCR. Below is the procedure for using promoter primers on BMAP clones (pT7T3D-PAC vector). Adjust to the established PCR conditions for clone specific primers (i.e. conditions used for primer design).

[PCR Recipe - 25ul]
| Item                  | Volume   |  
| :-------------------- | :------- |  
| Qiagen Tag Buffer     | 2.5ul    |  
| 10mM dNTPs            | 0.5ul    |  
| 10uM forward primer   | 1.25ul   |  
| 10uM reverseT7 primer | 1.25ul   |  
| Qiagen Taq Poly.      | 0.125ul  |  
| Water                 | 18.375ul |  
| Colony Lysate         | 1ul      |  

[PCR Conditions]
|Temp|Time|Cycles|
|:----|:-------|:---|
|94C|3min  | -> 1     |
|94C|40sec| \|          |
|48C|40sec| \| -> 35|
|72C|2min  | \|           |
|72C|5min  |-> 1       |

Run 5ul on a 1.2% agarose gel. Select one of the six that represents the expected product and amplified well.  Usually all 6 or at least 4 of the six agree in size so those are the ones to pick from.

###In vitro transcription

Use 10ul-12.5ul of the PCR product directly in a standard 20ul *in vitro* transcription reaction to produce DIG labeled probe (Lab/Roche protocol).  Probe is column purified, quantified and diluted to a 20X concentration for storage at-80C (whole-mount protocol).

We have found using the PCR product directly results in excellent probe without any degradation. Using PCR cleanup columns or phenol/chloroform extraction is not necessary. 

##Materials
- Reagents
	- Triton X-100
	- Tris pH 8.0
	- EDTA pH 8.0
	- PCR reagents
	- PCR primers
- Solutions

##Troubleshooting
Typically at least 5 of the colonies result in a PCR product and these will all match in size. If there is disagreement between sizes, especially when using promoter specific primers, it is recommended to discard the plate and find a new clone to try. When using clone specific primers and no product results, trying the PCR one additional time at a slightly elevated temperature (add 2C to the annealing temperature) may result be successful. Repeating more than once has proved useless.

##Discussion


##References
##Attribution
####Metadata
- Date created: 2002-10-10
- Date updated: 2009-02-17
- Version: 1

