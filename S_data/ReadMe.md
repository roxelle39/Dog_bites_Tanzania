Overview

This dataset provides ward-level, monthly records on rabies-related human bite incidents, rabies-related deaths, demographic profiles, environmental covariates, and dog population estimates for selected wards in the Kilombero and Ulanga districts of Tanzania.

It is suitable for:

    Descriptive analysis of rabies bite and death trends

    Statistical and spatial modeling

    Linking rabies data with environmental and socio-economic covariates

File Information

    File names: Bite_death_WD_cov.csv, Bite_death_WD_cov.shp and Ward.shp

    File type: CSV (comma-separated values) and shapefile(s)

    Number of records: 
        Bite_death_WD_cov.csv: 9,744 records
        Bite_death_WD_cov.shp: 9,744 records
        Ward.shp: 42 ward polygons

    Spatial resolution: Ward-level

    Temporal coverage: January 2006 – April 2025

    Projection: UTM_Zone_37_Southern_Hemisphere or EPSG:32737	in meters

Descriptions

Column	    Description
Regn_Cd	    Region code (numeric identifier for the region).
Regn_Nm	    Region name.
Dstrc_C	    District code (numeric identifier for the district).
Dstrc_N	    District name.
Ward_Cd	    Ward code (numeric identifier for the ward).
Ward_Nm	    Ward name.
WardCod	    Alternative ward code (possibly administrative).
ttl_bth	    Total human population in the ward.
totl_ml	    Total male population in the ward.
totl_fm	    Total female population in the ward.
Ar_kmsq	    Ward area in square kilometers.
wwid	      Ward-wide ID formed from district and ward names (two-part identifier).
ID_ward	    Numeric ward ID.
Yr_bttn	    Year of record for bite data.
Mnth_bt	    Month of record for bite data.
id_year	    Sequential ID for each year in the dataset.
id_yr_m	    Sequential ID for each year-month combination.
Date	      Year-month-day date (day fixed at 1 for all records).
bit_cnt	    Monthly count of reported human rabies bite incidents in the ward.
dth_cnt	    Monthly count of reported human deaths resulting from rabies bites in the ward.
nwctgry	    Settlement category (e.g., Rural, Urban).
prtctd_	    Protected area indicator: 1 if ward overlaps with protected area; 0 otherwise.
lnd_cvr	    Land cover category (five levels: 1 = Forest, 2 = Shrubland & savannas, 3 = Croplands (including vegetation), 4 = Wetlands, 5 = Urban and build-up lands).
pvrty_n	    Poverty index (takes values between 0 and 1. Whereas the higher the value the poorer the area).
elevatn	    Mean elevation of the ward (meters).
pop_den	    Population density (people per km²).
dogpop	    Estimated dog population in the ward.
vdogs	      Number of vaccinated dogs.




Note: The dataset does not provide the expected number of rabies bites or deaths. You will need to calculate these values yourself.

