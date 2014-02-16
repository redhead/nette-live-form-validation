Nette Live Form Validation (for Nette 2.0)
==========================================

Turn the default alert-based client-side form validation to nice live validation!

About
-----

JavaScript file based on JS validation of Nette Framework that adds live validation support for Nette 2.0 forms.


Installation
-----------------------
All you need is to link JS file from [ gist | https://gist.github.com/552273] on GitHub to you document. That's it!

The script works without the original ´netteForms.js´ file.

Options
------------------
- controlErrorClass - CSS class which is set to incorrectly filled form input
- errorMessageClass - CSS class which is set to error message
- validMessageClass - CSS class which is set to message if input is correctly filled
- showValid - boolean - show or hide message if input is correctly filled
- messageTag - HTML tag which will containt the message
- messageIdPostfix - string - postfix of id attribute of message tag

Further more, you can edit methods addError (shows error msg.), removeError (hides error msg.), showValid (show message if input is correctly filled), setupHandlers (sets handlers up for inputs, like focus, blur, onkeyup). These methods can be altered to support some JS framework, ie. jQuery.
