# Prerequisites
node (https://nodejs.org/en/download/)

# Install
    npm install

# Setup Config File
Setup a JSON configuration file (optional - you can use command line arguments as well)

    {
        "dir": "/Users/ice/Documents/DataToUpload",
        "folder": "MyDataImport",
        "host": "sample.ice5.ca",
        "username": "uploader001",
        "password": "h3llow0rld"
    }

# Running
    node main.js -c config.json

# Sample Result

    $ node main.js -c config.json
    Directory [OK]:     /Users/ice/Documents/DataToUpload
    Files [OK]:         1806 queued for upload.
    Host [OK]:          sample.ice5.ca                            
    Username [OK]:      uploader001
    Password [OK]:      ********
    Login [OK]:         Login success              
    Folder [OK]:        MyDataImport
    Uploaded:           1806/1806 (0 errors)
    
    Complete.