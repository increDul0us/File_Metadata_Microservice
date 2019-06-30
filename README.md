# File Metadata Microservice :file_folder:

This service accepts a file upload with a size limit of 1000KB. Once uploaded, it will return the file size in bytes in the JSON response. Note: This service is removing the file from the server right after sending the json response because the upload files are not being managed for this project.  


A Full Stack Javascript application built using [Node.js](https://nodejs.org/), [Express](https://expressjs.com/) and [Multer](https://www.npmjs.com/package/multer).
An API Project for FreeCodeCamp.

## Example Usage
You can drag or select a file from your computer and preview the file to upload. Once you click the upload button, the POST request is sent to the '/get-file-size/' API endpoint.

## Example Output

The server responds back with the file name and file size in the JSON response.

```javascript
{ 
  file_name: "incredulous.jpg", 
  file_size: "628521 bytes"
}
```


Cheers!!! :black_heart:
