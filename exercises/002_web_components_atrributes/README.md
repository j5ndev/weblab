# Web Components - Attributes

This experiment is a simple web component that writes a message using the name attribute.
The example referenced was [here](https://kinsta.com/blog/web-components/#adding-attributes).
Note that the example in the link had multiple issues to work through:

* When `HTMLElement` is used instead of `HTMLParagraphElement` there is an error: `Uncaught TypeError: Illegal constructor.` TODO: Better understand the cause of this error and find alternate ways to solve it.
* Updating the element's name field was not sufficient to update the message.

## How To Use It

Open index.htm in a browser and execute the following command in the console:
```js
document.getElementById("ha").setAttribute("name", "Logan");
```
After executing the command, the message should change from `Hello, Frank` to `Hello, Logan`.
