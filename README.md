# linkunderline
jQuery plugin to create an animated underline under the text links.

To create an animated underline on a link, you create a navigation with UL element and anchor elements, and invoke linkUnderlineAnim method with optional parameters 'speed' and 'color'.

<br>
<br>

<a href="http://www.vasil.cf/linkunderanim/demo1.html">DEMO 1</a>

Example 1 (creates the animated underlines with default values: speed = 0.3 seconds, color = "#DB3340", thickness = 2 and distance = 0)

<b>HTML</b>

&lt;ul id="links"&gt;

&lt;li><a href=""&gt;First link&gt;/a&gt;

&lt;li><a href=""&gt;Second link&gt;/a&gt;

&lt;li><a href=""&gt;Third link&gt;/a&gt;

&lt;/ul&gt;


<b>JS</b>

$("links").linkUnderlineAnim();



<a href="http://www.vasil.cf/linkunderanim/demo1.html">DEMO 2</a>

Example 2 (creates the animated underlines with options: speed = 0.3 seconds, color = "green", thickness = 3 and distance = 2)

<b>HTML</b>

&lt;ul id="links"&gt;

&lt;li><a href=""&gt;First link&gt;/a&gt;

&lt;li><a href=""&gt;Second link&gt;/a&gt;

&lt;li><a href=""&gt;Third link&gt;/a&gt;

&lt;/ul&gt;


<b>JS</b>

$("#links").linkUnderlineAnim({

	speed: 600,  //speed of underline animation (ms)
     
	color: "green", // color of underline (can be any CSS3 compatible color
      
	thickness: 3, // thickness of underline (px)
      
	distance: 2 // distance of the underline from the text (px)
      
}); //this uses the customized options



<b>OPTIONS</b>

<i>speed</i> - speed of underline animation (ms) (default 300)
        
<i>color</i> - color of underline (can be any CSS3 compatible color (default "#DB3340")
        
<i>thickness</i> - thickness of underline (px) (default 2)
       
<i>distance</i> - distance of the underline from the text (px) (default 0)
        
        
