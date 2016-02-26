Natural Gallery
============================

Use distribution on your project 
-----

The bower install does not include sources and build process. To run the demo, look at the end of this readme. 

Install natural-gallery :

```bower install natural-gallery --save```

Include photoswipe and natural gallery stylesheets + jquery script in your headers : 

```
<link rel="stylesheet" href="bower_components/photoswipe/dist/default-skin/default-skin.css">
<link rel="stylesheet" href="bower_components/photoswipe/dist/photoswipe.css">
<link rel="stylesheet" href="bower_components/natural-gallery/dist/themes/natural.css">
<link rel="stylesheet" href="bower_components/natural-gallery/dist/natural-gallery.min.css">
<script src="bower_components/jquery/dist/jquery.js"></script>
```

Includes photoswipe and natural gallery scripts in your footer: 

```
<script src="bower_components/photoswipe/dist/photoswipe.js"></script>
<script src="bower_components/photoswipe/dist/photoswipe-ui-default.js"></script>
<script src="bower_components/natural-gallery/dist/natural-gallery.min.js"></script>
```

Run and look at the demo for code implementation
-----

Clone project on your local disk :

```
git clone git@github.com:Ecodev/natural-gallery.git 
cd natural-gallery
```

Install production and dev dependencies and run build :

```
bower install && npm run build
```

Open demo/*.html with your preferred browser and editor.


Credits
============================

Icons made by [Freepik](http://www.freepik.com) and [Zurb](http://www.flaticon.com/authors/zurb) from [www.flaticon.com](http://www.flaticon.com) is licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/)
