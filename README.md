Image2JS
========

This was created as a joke in response to a post on clientsfromhell.net

[http://clientsfromhell.net/post/38159206859/the-images-need-to-be-in-javascript-format](http://clientsfromhell.net/post/38159206859/the-images-need-to-be-in-javascript-format)

Converts images so that they can be included on the page with a script tag 
instead of a boring old img tag. See the test.html file included for an example
of how to include the file properly.

Works with Python 2.6 and 2.7 as far as my testing showed.

Usage
-----

(Linux, or anything with shebang support for Python)

./image2js test.jpg

(Windows or anything else with no shebang support)

python image2js test.jpg

This will create a file called test.js in your current working directory.

Currently supports jpg, jpeg, png, and gif. It could probably support more, if
I added them to the list of accepted mimetypes, but I figured I'd play it safe.
