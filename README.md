jbar is a jQuery plugin that transforms an unordered list (`<ul>`) into a toolbar with dropdown menus.


Usage
-----

jbar requires jQuery 1.4 or higher.
Copy jquery.jbar.js and jbar.css to your server and reference them.
Call .jbar() on your menu elements.
  
    <link href="/stylesheets/jbar.css" media="screen" rel="stylesheet" type="text/css" />
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.2/jquery.min.js" type="text/javascript"></script>
    <script src="/javascripts/jquery.jbar.js" type="text/javascript"></script>
    <script type="text/javascript">
      jQuery(function(){ 
        jQuery('.jbar').jbar();
      });
    </script>
  
  

Javan Makhmali :: javan@javan.us