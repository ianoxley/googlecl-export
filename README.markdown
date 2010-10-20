googlecl-export
===============
This is a bash shell script to export documents from Google Docs using the GoogleCL command line tool. You can run it as follows:

    googlecl-export [-f format] [-d folder] | [-h]

Options
-------
* -f  The format you want to export the documents in (default is pdf; can be any format supported by GoogleCL)
* -d  The Google Docs folder of documents you want to export (default is all documents)

GoogleCL can be downloaded from [http://code.google.com/p/googlecl/](http://code.google.com/p/googlecl/)

Examples
--------
Export all documents in the reports folder to PDF:
    googlecl-export -f pdf -d reports

Export all documents to plain text (*warning*: you _may_ have to specify a destination for each file as there doesn't seem to be a way to pass a destination to googlecl according to the documentation):
    googlecl-export -f txt

