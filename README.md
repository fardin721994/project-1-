# project-1-

### Install node js

Visit the node js website using this [link](https://nodejs.org/en/download) and download the LTS version for your OS. The installation process is quite simple.

### Test node js

Open the command prompt and run this command:

```
node -v
```

the result would be something like this: v16.16.0

### Test npm

Open the command prompt and run this command:

```
npm -v
```

the result would be something like this: 8.11.0

### Start the project
1) Create a new folder.
2) Open vs code and select that folder.
3) Open the terminal in vs code and run this command:

```
npm init
```

After that just press Enter until finish.

This command will create a package.json file which is necessary for our project. 

### Install nodemon

Install nodemon as a development dependency:

```
npm install --save-dev nodemon
```

After that go to the package.json file and in the "scripts" part, replace this :

```
"test": "echo \"Error: no test specified\" && exit 1"
```

with this:

```
"start": "nodemon index.js"
```

From now on we can start our server using this command:

```
npm start
```

### Install other dependencies:

```
npm install express
```

```
npm install express-validator
```

```
npm install body-parser
```

```
npm install mongoose
```

```
npm install --save mongoose-unique-validator
```
