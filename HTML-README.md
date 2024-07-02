# How to write an HTML Boilerplate

This HTML boilerplate serves as a foundational template for creating webpages. It includes essential HTML5 elements and meta tags to ensure proper document structure, semantics, and compatibility across different browsers and devices.([MDN DOC](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)).

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Page Title</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    
</body>
</html>
```
>Tip: Click Shift + 1 + Tab.
## Explanation:

* **`<!DOCTYPE html>`**: Declares the document type and version of HTML being used.

* **`<html lang="en">`**: Defines the root element of the HTML document and specifies the document's language (English in this case).

* **`<head>`**: The section of an HTML document contains essential meta tags, character encoding, viewport settings, and links to external stylesheets and scripts, ensuring proper display and functionality across devices and browsers.

* **`<meta charset="UTF-8">`**: Specifies the character encoding of the document.

* **`<title>`**: Sets the title of the webpage, displayed in the browser tab.
* Sets the viewport to the width of the device and initial zoom level, ensuring proper scaling on different devices.
`<meta name="viewport" content="width=device-width, initial-scale=1.0">`

* **link**: Links an external stylesheet *styles.css* to apply styling to the webpage.

* **script**: Links an external JavaScript file *script.js* with the *defer* attribute, ensuring it loads after the HTML content.

* **body**: Contains the visible content of the webpage, including headers `<header>`, navigation menus `<nav>`, main content areas `<main>`, sections `<section>`, and footers `<footer>`.

* **Semantic Elements**: Uses HTML5 semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) to organize and structure content logically.
