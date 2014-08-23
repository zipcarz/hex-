hex-
====
jQuery(selector [, context])
jQuery(element)
jQuery(object)jQuery(elementArray)
jQuery(jQuery object)
<!DOCTYPE html>
<html>
<head>
  <script src="http://code.jquery.com/jquery-latest.js"></script>
</head>
<body>
  <p>one</p> <div><p>two</p></div> <p>three</p>
<script>
  $("div > p").css("border", "1px solid gray");
</script>

</body>
</html>
$("input:radio", document.forms[0]);
$("div", xml.responseXML);$(myForm.elements).hide()
jQuery(html [, ownerDocument])jQuery(html, props)
$("<div/>", {
  "class": "test",
  text: "Click me!",
  click: function(){
    $(this).toggleClass("test");
  }
}).appendTo("body");
