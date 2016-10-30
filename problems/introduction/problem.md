To keep things organized, let's create a folder for this workshop. 

Run this command to make a directory called `designpatterns` (or something else if you like):

```bash
mkdir designpatterns
```

Change directory into the `designpatterns` folder:

```bash
cd designpatterns
```

Create a file named `introduction.js`:

```bash
touch introduction.js
```

Or if you're on Windows: 
```bash
type NUL > introduction.js
```
(`type` is part of the command!)

Open the file in your favorite editor, and add this text:

```js
console.log('hello');
```

Save the file, then check to see if your program is correct by running this command:

```bash
yatichiri verify introduction.js
```

By the way, throughout this tutorial, you can give the file you work with any name you like, so if you want to use something like `catsAreAwesome.js` file for every exercise, you can do that. Just make sure to run:

```bash
yatichiri verify catsAreAwesome.js
```

