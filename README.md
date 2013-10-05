Paper Directory
================

This is a simple gem build to help the Cassville Church of Christ create its member directory.

Installation
------------

On a Unix (Mac OS X/Linux) system, run the following:
```
wget https://github.com/grantcupps/paper_directory/releases/download/1.1.0/cocdir-1.1.0.gem
gem install cocdir
```

Usage
-----
To run the application, you'll need the Master Contact Spreadsheet in CSV format and all of the photos listing in the Master Contact Spreadsheet. Assuming you have these, run the following command from the directory containing the CSV file and the directory of photos.<br/><br/>
`cocdir -s CSV_FILE -p PHOTO_DIRECTORY`<br/><br>
CSV_FILE is the name of the CSV file (e.g. "spreadsheet.csv") and PHOTO_DIRECTORY is the name of the directory containing the photos (e.g. "photos2"). 


