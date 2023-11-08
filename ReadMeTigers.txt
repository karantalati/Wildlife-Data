ReadMe file for 10 year tiger dataset from Nagarahole Reserve, India.

These data were collected by Wildlife Conservation Society under the supervision of Dr. Ullas Karanth and are the joint intellectual 
property of entities. These data have been published in full or in part in Karanth 1995; Karanth et al. 2006; Karanth and Nichols 1998; 
Karanth and Sunquist 2000.

EECam_act.csv - this file contains each camera and the number of occasions it was active during each of the 10 years.  
		The file contains 195 traps (dim: 196 x 11). Camera trap 188 is not included.
	Trap_ID: the camera trap identifier
	Column names 1-10: These represent each primary period. The values within each column are the number of occassions that the camera trap was
			   active during each primary period; zero indicates it was not operational during that primary period. 

EERecords.csv - this file contains each tiger capture, the trap, the occasion, and the primary period (note, we do not include the occasion 
		in the our analysis). These data represent 75 unique tigers captured in 111 unique camera traps 
	Ind: This is each unique tiger
	Trap_ID: the camera trap identifier (for each trap the tiger was captured on)
	Occasion: the sampling occasion within the primary period for each capture
	Primary Period: This is the primary period for each capture

 
EEtraplocs.csv - this file contains the trap number, x, y coordinates for each camera.  Some camera locations are still used, so 
		these locations are centered to protect the exact locations. The file contains 195 traps (dim: 196 x 3).
   	Trap_ID: the camera trap identifier
	Centeredx: The x-coordinate of the camera trap location (centered to remove precise locations) given in meters.
	Centeredy: The y-coordinate of the camera trap location (centered to remove precise locations) given in meters.


The number of days within each primary period is given in Karanth et al. 2006 Table 1. Summarized here:
Primary Period	No. Days
1		162
2		127
3		75
4		197
5		78
6		118
7		33
8		39
9		47
10		54