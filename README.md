### Visual Presentation

![How WhatsApp ticks work](./assets/media/how-whatsapp-ticks-work.png)
Fork this repository and try to experiment by changing the .JSON files in folder:   
courses-data/how-whatsapp-ticks-work  

Try to change  
+ content.json and 
+ diagram.json files  
and see the differences.

---

#### Run local webserver

You can run a local web server to see changes locally on your machine.

Check this link [https://stackoverflow.com/a/8427954](https://stackoverflow.com/a/8427954) to know about "Using node.js as a simple web server".   

First [get npm](https://www.npmjs.com/get-npm) by [installing NodeJS](https://nodejs.org/en/).

---

So the steps after you fork the repository and clone it to your machine.  

1. Install NodeJS from [here](https://nodejs.org/en/).

2. Change directory to your repo folder in your machine and install connect and serve-static with NPM

```
$ cd visual-presentation
$ npm install connect serve-static
```

3. Run with Node.js

```
$ node server.js
```

4. You can now go to http://localhost:8080 and see your files.


