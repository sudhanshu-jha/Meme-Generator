#### Redux Meme Generator 

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/2f21b4aa51c64108bdf49ff9ffd95ea0)](https://www.codacy.com/app/sudhanshu-jha/Meme-Generator?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=sudhanshu-jha/Meme-Generator&amp;utm_campaign=Badge_Grade)
[![Build Status](https://travis-ci.com/sudhanshu-jha/Meme-Generator.svg?branch=master)](https://travis-ci.com/sudhanshu-jha/Meme-Generator)

This React/Redux application uses the ImgFlip API, Redux, Fetch API to create a meme and see the result within the same webapp. 

To run this locally, you need to make an account at https://imgflip.com/. 

run: 

1. `git clone git@github.com:wlee367/Redux-Meme-Generator.git`
2. `cd Redux-Meme-Generator`
3. `vim src/actions/secrets.js`
4. In secrets.js file, put your username and password of your imgflip account like so: 

```javascript
const username = 'yourusername';
const password = 'yourpassword';

export {username, password};
```
5. `npm install`
6. `npm start`
7. visit http://localhost:3000
