# Talentreef Coding Sample
The objective is to build a view that conforms to the spec provided by Talentreef. 

[spec image](./TableLayoutTest.png)

The result, served from /public/index.html, can be seen [here](https://simonsheridan.github.io/TR-code-challenge/public)

## To run locally
* Clone this repo
* open /public/index.html in a browser
* (optional dev setup)
* `npm install`
* `gulp` - This builds the compiled css file (from the scss stylesheets) and starts the watcher

## Some additional thoughts
The things I feel are missing from a more production-like scenario are:
* HTML composition.  The HTML is all in one file, in production it would be split out into different HTML templates via EJS, Angular templates, React JSX, etc.
* stylelint.  I would add [stylelint](https://github.com/stylelint/stylelint)
