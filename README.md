# hisp-project
DHIS2 is a free and open source health information system software package based
on Java frameworks. Traditional method being used by public health Systems which
have been recording aggregate data of the services provided across various health
programmes.
This is crucial in monitoring reach and availability of public health services, but it
lacks the ability of tracing the persons being provided with these services and quality
of these ones. It is important that treatment information of each person is maintained
as an individual case which can provide a comprehensive data management solution
based on data warehousing principles.

There is a need to allow users to import the malaria(and other) cases and their
events in DHIS 2 through excel sheets due to the following 2 reasons­
1. Non­availability of internet all the time.
2. Simplify the process as registering and recording event for each case takes some
time while multiple records are to be reported. It makes it easier to report them on
excel and then import the excel sheet.
The import needs to map the case based data to the selected org unit and period. It
also involves identifying and giving alerts for any error or duplicate records.
In terms of DHIS2, the import should do the following­
➢ Register the tracked entity which is person
➢ Enroll him to malaria program
➢ Report the event for the treatment given

The primary feature and the main objective of the project include ​:­
➢ Importing patient records registered in the excel sheet.
➢ Import CCD/XML exports from an EMR into DHIS2 tracker.
➢ Location capture for patient using geolocation.
