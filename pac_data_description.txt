National Survey of Pediatric Post-Acute Care: An Open-Access Database of Pediatric Facilities We identified and surveyed facilities that provide post-acute care to pediatric patients across the United States and created a database of these findings. For specific methods, please see our manuscript.Please contact us at xxxx@gmail.comFile Creation Date: 03/31/2023 
Short description of database variables Variable name: STATE
Description: Identifies the US state in which the facility resides
Values: United States Postal Service state abbreviation 
 
Variable name: FAC_NAME
Description: Identifies the name of the facility 
Values: As listed in state registries of licensed health care facilities
 
Variable name: ST_ADR
Description: Identifies street address of facility
Values: As listed in state registries of licensed health care facilities
 
Variable name: PHONE
Description: Identifies phone number of facility
Values: As listed in state registries of licensed health care facilities
 
Variable name: INPT_BEDS
Description: Number of inpatient beds at facility
Values: Inpatient beds as listed in state registries of licensed health care facilities or verified by survey or online, only reflective of pediatric post-acute care beds if STATUS=1 (see below)
 
Variable name: ADMIT_AGE_MIN
Description: Minimum age considered for admission to the facility 
Values: number
 
Variable name: ADMIT_AGE_MAX
Description: Maximum age considered for admission to the facility 
Values: number
 
Variable name: TRACH
Description: Facility accepts patients with tracheostomy
Values:            0= no
                   1= yes
                   2= case-by-case
                   3= unknown
            
Variable name: VENT
Description: Facility accepts patients with tracheostomy requiring mechanical ventilation
Values:            0= no
                   1= yes
                   2= case-by-case
                   3= unknown
 
Variable name: PN
Description: Facility accepts patients requiring total parenteral nutrition.
Values:            0= no
                   1= yes
                   2= case-by-case
                   3= unknown
 
Variable name: STATUS
Description: Patient population accepted by facility
Values:            1= Facility accepts pediatric patients 
                   2= Facility accepts adolescent patients
                   3= Facility accepts pediatric patients on a case-by-case basis 
 
Variable name: PRVDR_NUM
Description: Identification number assigned to a certified provider by the Center for Medicare and Medicaid Services (CMS)
Values:            5 or 6-character alphanumeric code 
                   ‘MISS’ prefix indicates facilities that could not be matched in CMS database
 
Variable name: ZIP
Description: Five-digit ZIP code for a facility’s physical address
Values:             5 digit numeric code 
 
Variable name: FREE
Description: For pediatric facilities only (ie where status=1). Indicates whether facility is free standing or whether post-acute care unit is embedded within another facility.
Values:             0= Embedded facility 
                    1= Freestanding facility
 
Variable name: LATITUDE
Variable name: latitude
Description: Latitude for a facility’s physical address
Values:		Numerical geocode 
 
Variable name: LONGITUDE
Description: longitude for a facility’s physical address
Values: 	Numerical geocode 
