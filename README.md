[NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) 
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

This is a simple web app with minimal frontend (literally a single page) that uses nodejs and npm packages along with mongodb to shorten urls. I assumed that it's a project for Egyptian audience, and made sure it's pretty user friendly by using the Egyptian dialect in a very casual manner. 

The key tool that made this project possible is [nanoid](https://www.npmjs.com/package/nanoid). When the user enter their url, say a terribly long link from an arab news website, nanoid generates what is called a "slug". A link combining the app's own domain with that slug is displayed to the user as an output, when it's clicked, it redirects to the intended page. 

[!alt text](https://i.ibb.co/cLShh9m/yo.png)
