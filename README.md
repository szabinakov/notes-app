# Notes taking app
#### Part of the [Node.js Udemy](https://www.udemy.com/course/nodejs-the-complete-guide/) course I have built an app which can take notes from your terminal

#### The app is able to:
+ Take notes with title and body 
+ Save the notes
+ Remove notes
+ List all 
+ Read the note you want to see

## Built with
+ Node.js <br />
_You can download Node.js from [here](https://nodejs.org/en/)_
+ npm <br />
_In your project folder:<br />_
```
npm init
```
+ Javascript 

## Used npm pacakges 
+ [Validator](https://www.npmjs.com/package/Validator)
+ [Yargs](https://www.npmjs.com/package/yargs)
+ [Chalk](https://www.npmjs.com/package/chalk)

## Example
As a first step open up your terminal and navigate in to your project folder. <br />
<br />
You are able to add notes with the following command: <br />
```
node app.js add --title="name-of-title" --body="name-of-body"
```
<br />
If the title is already taken you would get an error message back, if the title is free the app let you add to the list with the body.
<br />

You are able to remove notes with the following command: <br />

```
node app.js remove --title="name-of-title" --body="name-of-body"
```
<br />
If the title does not exist yet you will get an error message back, otherwise with removing the matching note you get a green succeed message.
