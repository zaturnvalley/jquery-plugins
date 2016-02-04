# jQuery Plugins Lab

Using your knowledge of jQuery and the various plugins available for it, we're going to build an application that lists content using tabs and accordions.

## Resources

* [jQuery API](https://api.jquery.com/)
* [jQuery UI](http://jqueryui.com/)

##Loading Dependencies

For this project you should be using jQuery and jQuery UI. Generally you can find the CDN for these by using google, but to get you up and running quickly we've included the CDN links below.

**Paste these in your `<head>` tag:**

```html
  <link rel="stylesheet" href="https://ajax.googleapis.com/ajax/libs/jqueryui/1.11.4/themes/smoothness/jquery-ui.css">
```

**Paste these before the `</body>` tag:**

```html
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
  <script src="https://ajax.googleapis.com/ajax/libs/jqueryui/1.11.4/jquery-ui.min.js"></script>
```

##Minimum Requirements

* A user should be able to view four different paragraphs of text using tabs. See [jQuery UI tabs](http://jqueryui.com/tabs/).

* Below the tabs, a user should be able to view four different images using accordions. See [jQuery UI accordions](http://jqueryui.com/accordion/).

* Text can be obtained via Wikipedia, news articles, or another source. Images can be obtained via a placeholder image site (like [placekitten](https://placekitten.com)).

##How to get started

1. Start by constructing a basic `index.html` page as your starting point.

2. Load the CDN for jQuery and jQuery UI.

3. Focus first on laying out your page with the appropriate elements, then work on writing the appropriate jQuery code.


## Bonus

* Include some other jQuery plugins that may interest you. Here are some commonly used ones:
  * [parallax.js](http://pixelcog.github.io/parallax.js/)
  * [Avgrund Modal](http://labs.voronianski.com/jquery.avgrund.js/)
  * [Bigvideo.js](http://dfcb.github.io/BigVideo.js/)

## Super Bonus

* Create your own jQuery plugin. Now that you've experimented with plugins, you'll be pleased to hear that making your own is actually pretty easy.
  * [jQuery Documentation for Custom Plugins](https://learn.jquery.com/plugins/basic-plugin-creation/)

## Super Super Bonus (this is pretty tough)

* Add a button that allows you to switch between displaying content in tabs and accordions. For example, if a button is added for the tabs of text, pressing it would display the text in accordions.
