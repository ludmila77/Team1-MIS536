SEER 21 2000-2016 Limited-Field Research Data in ASCII Text Format   April 15, 2019

The following is a description of the contents of the 
SEER21_LIMITED_2000_2016_TEXTDATA directory for the 2000-2016 limited-Field 
Research Data.  The data in this directory are stored in ASCII text format 
and must be analyzed with your own statistical/analytical software.

Additional information regarding the SEER 1975-2016 Research Data is located
on the SEER Web site at:
     http://seer.cancer.gov/data

This TEXTDATA directory contains the following:

     - SEER Cancer Incidence Research Database for patients diagnosed
       2000-2016
     - County level population estimates for the SEER registries by 19 age
       groups and single ages from the Census Bureau for 2000-2016
     - Data dictionaries for the SEER and population data

Similar in nature to the previous 1973-2015 version of data with the 
July - December 2005 Louisiana diagnoses being distributed as a supplement 
to the SEER Research Data.  Hurricane Katrina had a large impact on Louisiana's 
population for this six month time period so these diagnoses are not analyzed in 
most SEER reporting.  Consequently, the populations include one decimal place.

Use of or citation of the data in a published document should
contain the following reference.
     Surveillance, Epidemiology, and End Results (SEER) Program
     (www.seer.cancer.gov) Research Data (1975-2016), National Cancer
     Institute, DCCPS, Surveillance Research Program,
     released April 2019, based on the November 2018 submission.

To reference an electronic copy of the most recent and previous versions of the
SEER Cancer Statistics Review (CSR) and other materials, please visit the SEER
Web site at:
     http://seer.cancer.gov

Some documentation contained with this data is in Portable Document Format (PDF).
The PDF files can be viewed and printed with the Adobe Acrobat Reader public
domain software provided at the Adobe Web site:
     http://www.adobe.com

The following paragraphs describe the general directory structure of the data.

  \INCIDENCE
     TEXTDATA.LIMITEDFIELD.FILEDESCRIPTION.PDF - Data dictionary for the 
     SEER incidence data files.
     Additional documentation is located on the SEER Web site:
       http://seer.cancer.gov/data
       
     READ.SEER.LIMITEDFIELD.RESEARCH.NOV2018.SAS - SAS code with input statement 
     only. Setup to read SEER 21 only, YR2005.LA_2ND_HALF files have same format.

     Sub-directories with the SEER November 2018 Limited-Field Research Data files.  
     The SEER November 2018 data within each sub-directory have been broken out
     into nine site group files.  The split into site files was made using the 
     Site recode ICD-O-3/WHO 2008.  These files are stored as ASCII text files.

     BREAST.TXT    -  Breast
     COLRECT.TXT   -  Colon and Rectum
     DIGOTHR.TXT   -  Other Digestive
     FEMGEN.TXT    -  Female Genital
     LYMYLEUK.TXT  -  Lymphoma of All Sites and Leukemia
     MALEGEN.TXT   -  Male Genital
     RESPIR.TXT    -  Respiratory
     URINARY.TXT   -  Urinary
     OTHER.TXT     -  All Other Sites

     YR2000_2016.SEER21
        This directory contains the SEER November 2018 Research Data files
        from 21 SEER registries for 2000-2016.  The registries are
        Atlanta, Connecticut, Detroit, Hawaii, Iowa,  New Mexico, San
        Francisco-Oakland, Seattle-Puget Sound, Utah, San Jose-Monterey, 
        Los Angeles, Rural Georgia and Alaska Natives, Greater California, 
        Kentucky, Louisiana, New Jersey, Greater Georgia, Idaho,
        Massachusetts, and New York.  For the year 2005, only January - June 
        diagnoses are included for Louisiana.  Hurricane Katrina had a large 
        impact on Louisiana's population for the July - December 2005 time 
        period.  For most SEER reporting, Louisiana cases diagnosed in the 
        latter half of 2005 are not analyzed.

     YR2005.LA_2ND_HALF
        This directory contains the July - December 2005 diagnoses for
        Louisiana from their November 2018 SEER submission.  Hurricane Katrina
        had a large impact on Louisiana's population for this six month time
        period.  For most SEER reporting, Louisiana cases diagnosed during this
        six month period are not analyzed.  These data are considered a
        supplement to the SEER Research Data.

   \POPULATIONS
     POPDIC.HTML - Data dictionary for the population data files
     Additional documentation is located on the SEER Web site:
       http://seer.cancer.gov/popdata

     Sub-directories with population files (19AGEGROUPS.TXT and SINGLEAGES.TXT)
     with estimates to match the registry/year coverage of the SEER Research
     Incidence Data for 1975-2016.  These files are stored as ASCII text files.
     
     EXPANDED.RACE.BY.HISPANIC\YR2000_2016.SEER21
        This directory contains population files for the Greater California,
        Kentucky, Louisiana, New Jersey, and Greater Georgia SEER registries 
        for 2000-2016.  For the year 2005, the Louisiana populations here are 
        meant to only be used with the January - June diagnoses.  The populations 
        are for the eight combinations of race and Hispanic origin.  The races 
        are White, Black, American Indian/Alaskan Native, and Asian or Pacific 
        Islander.  Hispanic origin has values of Hispanic and non-Hispanic.

     EXPANDED.RACE.BY.HISPANIC\YR2005.LA_2ND_HALF
        This directory contains population files to be utilized with the
        July - December 2005 Louisiana diagnoses.  The populations are for the
        eight combinations of race and Hispanic origin.  The races are White,
        Black, American Indian/Alaskan Native, and Asian or Pacific Islander.
        Hispanic origin has values of Hispanic and non-Hispanic.

----------------
REVISION HISTORY
----------------
4/15/2019 - Initial Release

