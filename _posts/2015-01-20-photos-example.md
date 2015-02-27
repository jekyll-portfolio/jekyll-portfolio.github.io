---
title:  "How to include photos"
description: "How to add photos and images to any given file"
thumbnail_url: "/images/thumbs/montana-hailstorm.jpg"
---



Remember to display individual photos on any post, you can use the `{{"{%"}} include widgets/post_image.html %}` statement:

~~~
{{ "{%" }} include widgets/post_image.html src="http://upload.wikimedia.org/wikipedia/commons/f/fb/Taser-x26.jpg" caption="A photo of the X26 taser model from Wikipedia." source_url="http://en.wikipedia.org/wiki/Taser#mediaviewer/File:Taser-x26.jpg" source_credit="Photo by jasonesbain - Taser. Licensed under CC BY 2.0 via Wikimedia Commons" %}
~~~

{% include widgets/post_image.html src="http://upload.wikimedia.org/wikipedia/commons/f/fb/Taser-x26.jpg" caption="A photo of the X26 taser model from Wikipedia." source_url="http://en.wikipedia.org/wiki/Taser#mediaviewer/File:Taser-x26.jpg" source_credit="Photo by jasonesbain - Taser. Licensed under CC BY 2.0 via Wikimedia Commons" %}



So it's possible to create a "gallery" of photos by making a series of those calls. 


