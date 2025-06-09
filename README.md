# xray
Extract crystallization conditions from pdb entries, do statistics, correlate with primary sequence features

# crystallization conditions
Crystallzation conditions are deposited alongside the structure and are present in the PDB header. [[rcsb.org]] allows the creation of custom seach reports. One can search for all structures that were determined by xray crystallography and then create a report that contains all the relevant pdb fields. This seems to be an efficient way to get all the required data. Probably best done via their [[https://www.rcsb.org/docs/programmatic-access/web-apis-overview | API]].