# Jquery-Flickr-Gallery
Simple Jquery Flickr Gallery

How to use:
- Get your flickr id visiting http://idgettr.com/
- Insert this code between <head> Tag:
```
	<script type=”text/javascript” src=”js/jquery.min.js”></script>
	<script type=”text/javascript” src=”js/jquery.prettyPhoto.js”></script>
	<script type=”text/javascript” src=”js/jquery.flikr-markeclaudio-gallery.js”></script>
	<link rel=”stylesheet” href=”style/prettyPhoto.css” type=”text/css” media=”screen” />
	<link rel=”stylesheet” href=”style/jquery.markeclaudio.flikrgallery.css” type=”text/css” media=”screen” />
	<script type=”text/javascript” charset=”utf-8″>
	$(document).ready(function(){
		markeclaudioFlickrBox(‘7733912@N04‘);   //<– Your flickr id
	});
	</script>
```
- Add a div with id=flickrbox where you want
```
<div id=’flickrbox’> </div>
```
- Here you can view a demo: http://www.claudiomarchesini.it/demo/flikr_gallery/
