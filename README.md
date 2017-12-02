# file_uploader

file_uploader is a utility developed based on NodeJS and ExpressJS to upload one or more files to server. It is a strait forward and simple web client demostrating the selection of files and uploading them to the server. Progressbar provides the visual indication of the upload progress.

Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Prerequisites

The application runs on Node JS and uses Express and Formidable
express: to handle the routes and serve up the HTML, CSS, and JS files
formidable: to parse the incoming form data containing the file uploads

Installing

npm install express formidable --save

Running the system

1. Run 'node app.js'
2. Open up the http://localhost:3000 in browser.
3. Select one or more files and submit to upload. Verify if they are uploaded under project's /uploads directory.

Deployment

Since it is a node JS application, the deployment is as simple as starting the app using 'node app.js' command. 

Built With
NodeJS, Express, Formiddable

Contributing

The credit to this first version goes in its entirety to the author @ https://coligo.io/building-ajax-file-uploader-with-node/

Versioning
1.0.0

Authors

Kalpit Patel - Initial work - Self learning purpose

License

The initial version is the work of the author @ https://coligo.io/building-ajax-file-uploader-with-node/ and hence the licensing terms shall be binding as per the terms set by the author. 
The subsequest updated version may be licensed under the MIT License - see the LICENSE.md file for details

Acknowledgments

Many thanks to the author @ https://coligo.io/building-ajax-file-uploader-with-node/. It has helped me quick start understanding some of the concepts of file uploading.
