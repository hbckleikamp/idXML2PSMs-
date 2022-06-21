# idXML2PSMs
single python script to convert .idXML files to PMSs format, which is generated by proteome discoverer. 
<br>This particular pipeline was used to generate  PSMs outputs for Calisp-2 without needing to use proteome discoverer.  

Script was designed to be run in Spyder 5.15 <br>
The variable 'files' should be edited to contain the full filepaths of the files that need to be processed. <br>
outputs are written to the directory of the input files.

<br>There are two script versions, one for inputs where modifications are listed in the idXML file with a delimiter '_modifications', and one where modifications of unknown masses are matched to unimod. 
The unimod version is also avaiable to convert pepXML to PSMs format for Calis-p

