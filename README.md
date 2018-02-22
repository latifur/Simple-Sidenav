# Simple-Sidenav
This is a Simple Sidenav Which I have Created For My own project. Any one who need a sidenav applicable with any framework and device you can use this sidenav

see the demo from here <br>https://latifur.github.io/Simple-Sidenav/Sidenav/

first you need to add  #sidenav.css <br><br>
&#x3C;link rel=&#x22;stylesheet&#x22; href=&#x22;css/sidenav.css&#x22;&#x3E;

you have to add jquery latest version

add this jQuery to your custom js <br><br>
$(&quot;.sidenav-toggler&quot;).on(&quot;click&quot;,function(){ <br> $(&quot;.sidenav&quot;).addClass(&quot;sidenav-show&quot;)<br> });<br>
$(&quot;.close-nav&quot;).on(&quot;click&quot;,function(){ <br>$(&quot;.sidenav&quot;).removeClass(&quot;sidenav-show&quot;) <br>});<br>
