# youtube
Making MERN Stack Youtube with Crop and resize functionality 


[![N|Solid](https://raw.githubusercontent.com/vashisth00/youtube/master/Screenshot%202020-12-24%20at%205.20.43%20AM.png?token=AHDX7GLITI2DSDIFFL2QCNS75UJUW)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://powerful-escarpment-46256.herokuapp.com)

Features:

The application allows users to upload video content. They can upload one video or multiple videos at once. 
Users can share their videos or watch a video shared by others. 

Install the dependencies and devDependencies and start the server + React using following Steps

```sh
$ git clone https://github.com/vashisth00/youtube.git
$ cd youtube
$ npm install
$ cd client
$ npm install
$ cd ..
$ npm run dev
```

- mongoose backend env on Heroku if you need access for DB let me know
- Responsive ANT Design
- Every Video has shareable hashed URL 
- Multi Video using Multer
- FFmpeg for Thumbnaiil
- Recommendation using created_at video
- JWT for login 

http://localhost:3000/video/upload
http://localhost:3000/video/5fe3ccb52c56cd85e1194540 => Shareable hash

# Upload

[![N|Solid](https://raw.githubusercontent.com/vashisth00/youtube/master/Screenshot%202020-12-24%20at%205.23.53%20AM.png?token=AHDX7GL6BMVA3VZ2O5H7IL275UKIA)](https://nodesource.com/products/nsolid)
  - Uploaded compressed videos go to Uploads Folder
  - FFmpeg thumbnails in uploads/thumbnail


Deployed on Heroku on free dynos so might crash sometimes : https://powerful-escarpment-46256.herokuapp.com/

