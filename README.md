Accessing the prosper-api
===========

## Goals
1. Get data fromprosper-api
2. Create tables in which to store said data
3. Basic descriptive stats
4. Modeling loss

Data sources

- http://www.p2panalytics.com/
- http://www.prosper.com/about/academics.aspx


Prosper API

- 2007 SVN Source  http://sourceforge.net/projects/prosperapi/

Data Definitions for Export

- http://www.prosper.com/Downloads/Services/Documentation/ProsperAPI_Objects_Details.html


[Prosper Data Export](http://www.prosper.com/tools/DataExport.aspx)

"
- Complete Data Download
  - [ProsperDataExport_xml.zip](https://services.prosper.com/DataExport/ProsperDataExport_xml.zip) (~550 MB) - A zip archive which contains the following files:
  - ProsperDataExport.xml (~1.7 GB) - The Prosper Market Export Data (except for bids) in XML format. Click here to view a condensed example of this file.
  - ProsperDataExportBids.xml (~2.5 GB) - The Prosper Market Export Data (bids only) in XML format.
  - ProsperDataExport.xsd (~13 KB) - The Schema Definition of the Export Data in XML format. Click here to view the file.
"

Prosper Snapshot (in XML)

- http://www.prosper.com/tools/

Prosper XML-CSV

- http://www.rateladder.com/2008/02/22/convert-prosper-xml-to-csv/
- JAR to run http://www.rateladder.com/images/ProsperXMLtoCSV.jar
- ```
java -jar ProsperXMLtoCSV.jar ProsperXMLFileLocation CSVDestinationDirectory
```