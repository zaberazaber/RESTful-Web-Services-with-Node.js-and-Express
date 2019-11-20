# RESTful-Web-Services-with-Node.js-and-Express


install eslint

```
npm i eslint -D
```
 -D add it to our dev dependencies instead of our regular dependencies. when we deploy this out somewhere and we npm install out in production, it's not going to take the time to install the dev dependencies. It's only going to install the actual dependencies.


add an eslint task in the pakage.jason script to avoid installing eslint globally When you run something from scripts, it looks in your node_modules first,

```
"scripts": {
    "lint": "eslint",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```

then we will run `npm run lint --init`  what this -- does is that it will pass anything after it to run after the value of the variable so 
this will be equal to 

npm run lint --init  --> npm run eslint init
