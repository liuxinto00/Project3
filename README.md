Readme
Project Description 
Welcome to Petube and watch cute animal videos! We are a web streaming application which offers online streaming of a library of our carefully selected videos. You can also sign up and log in to add your comments and likes to your favorite videos. It’s like a Netflix for animal lovers and a happy place that will melt your heart.

In the homepage, you can see all of our curated videos. You can just watch the videos on the homepage. If you want to get interactive, you can click the title of the video you’re interested, which will bring you to the video’s own page. Once you registered and logged in, you can add comments and likes to express your opinion about the video!


Instruction to Build
The database is on MongoDB Atlas and the website is hosted on heroku here. To install and run, do the following: 
git clone https://github.com/liuxinto00/Project2 

cd Project2

Due to security reasons, we didn’t include our MongoDB Altas uri which contain username and password information. To run this downloaded application, you need to change 3 places with your own MongoDB atlas uri. 

Go to db/myMongoDB.js and change line 7 to 
	const uri = “your own uri”;

Go to routes/users.js and change line 7 to
	const url = “your own uri”;

Go to routes/videos.js and change line 8 to
	const url = “your own uri”;

You may not see any videos on the website. That’s because your MongoDB Atlas doesn’t have any data yet.
yarn install

yarn start

cd front

yarn install

yarn build

yarn start


Project Objective
Learn and explore the popular and powerful MERN stack techologies(MongoDB, Express.js, React, and Node.js)to building dynamic web sites and web applications. Because all components of the MERN stack support programs that are written in JavaScript, we can learn more about Javascript via building the MERN applicationsusing one language for both server-side and client-side execution environments.

Author
Xintong Liu & Michelle Duan

Class Link: 
CS 5610 Web Development
https://johnguerra.co/classes/webDevelopment_fall_2020/

Licence
This project is under MIT license.

Screenshot
￼
￼

Demo Video
Watch our web application demo video here:
https://youtu.be/C7Lcwc9Ncc8
