BlockDegree node-v14.21.3

- npm i redis - for client error
- npm i gulp
- .nvmrc :- to automatically switch to the specified Node. js version when you navigate to the project directory

- # If you are facing issue realted to (POST /api/getAuthStatus 500 22.966 ms - 9532)
- fill the 'secret' key in app.js file.

- talked about package.lock file :- 
to ensure that the same dependencies are installed consistently across different environments, such as development and production environments.

- while running new-admin on same port we are running npm run build command that time facing some error 

- Error MacOS Monterey 12.3 no longer has Python 2.7 installed, finding it very difficult to use sqlite3 

solve with this {
-brew install pyenv
-pyenv install 2.7.18 and then pyenv global 2.7.18
-export PATH="${HOME}/.pyenv/shims:${PATH}"
-npm install sqlite3
}

- Error Node Sass could not find a binding for your current environment
solve with this {
npm rebuild node-sass
}

.env 
{
    posted wrong admin id in .env file
}

- result showing wrong in wallet course and wrong question array 
 soluction 
 add the question in db using studio3T
 

8th Feb 

-added the 
-new categories
-the blogs
-added the courses
-motivational lines
-Frequently asked questions
-On the top of the course page, we'll add a button labeled 'Welcome.' When users click on this button, it will take them on thw Welcome Page
-enable the "drip content" feature, it means that as an admin, you set the course completion percentage to 20. If the percentage is not met by the user, they won't be able to access the next lectures.