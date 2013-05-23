#Compass Sprite Boilerplate

A base project for generate your sprite using [Compass](http://compass-style.org/)

---
## Instructions

First, you need to have Compass instaled, if you dont, please follow [these](http://compass-style.org/install/) instructions.

With the Compass instaled you need:

- Clone the repository

```bash
$ git clone git@github.com:<your-github-username>/compass-sprite-boilerplate.git
```

- Enter in the folder

```bash
$ cd compass-sprite-boilerplate
```

##Structure

<pre>
.
|-- stylesheets/
|-- sass/
|-- images/
|   |-- your_folder (in this project is "icons")
`-- config.rb
`-- index.html
</pre>

##How to use

- Insert your images in the "your_folder"
- Change the file: "sass/style.scss" with your information
- Run compass

```bash
$ compass watch
```

And, is just that! Your sprite is generated on the "images" folder, and the css code in ```css/style.css```

Obs.: If you have problens with folders path, change the location of your sprite in the ```css/style.css``` > ```background: url('')```

##Docs

- [Compass Sprite Tutorial](http://compass-style.org/help/tutorials/spriting)
- [CSS Sprite Sheets: Best Practices, Tools and Helpful Applications](http://webdesign.tutsplus.com/tutorials/htmlcss-tutorials/css-sprite-sheets-best-practices-tools-and-helpful-applications/)