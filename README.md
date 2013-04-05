autoSave
===========
A autoSave jQuery Plugin

How to use:
-------------------------

1. Include necessary JS files

	```
	<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
	<script src="js/jquery.autoSave.min.js"></script>
  	```

2. Add autoSave CSS file. Please tweak it to serve your needs.

	```
	<link rel="stylesheet" href="css/style.css" />
	```

3. Create the following HTML element

	```
	<textarea id="text"></textarea>
	<span id="msg"></span>
	```

4. Fire plugin using jQuery selector

	```
	$(function() {
		$("#tabs").autoSave(callback, ms);
	});
	```
	ms allows to delay callback function. default value is 2 seconds.

5. Example

	```
	$("#text").autoSave(function() {
		var time = new Date().getTime();
		$("#msg").text("Draft Autosaved " + time);
	}, 2000);
	```
	
6. Have fun:-)


Compatibility:
-------------------------

* IE7 and above, Firefox, Chrome, Safari and Opera
	
Live Demo:
-------------------------

* [Homepage](http://www.geniuscarrier.com)
* [Demo](http://www.geniuscarrier.com/demo/autoSave/autoSave.html)
