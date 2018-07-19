# *About Myself*

![Image](IMG_7921.jpg)

- I am a Junior at George Mason University, studying Psychology with a concentration in Human Factors and Applied Cognition with a double minor in Neuroscience and Bioengineering.
- I have an avid interest in Humanoid robotics, Cybernetics, and Human Computer Interfaces/Interaction.
- I plan on using this site to publish material and images/posts and descriptions of the different projects that I've done/been involved with and am currently doing. 


## *Major Projects*

  - RAT-BOT
  
  - MAKI
  
  - FlapJack
   
  - Cozmo
  
# *Things I've Tinkered With*

   - Autonomous Spoon Feeder for Patients with Tremours
   
   - Design of Multistage Electron Microscope Adapter
   
   - Area Image Processing of Aneurysm Prevention Device

   - Voice Controlled Non-Hollonomic Bot
  
   - Radioshack Decsion Maker
  
   - Google Voice
  
## Publications
### Header 3

**Bold** and _Italic_ and `Code` text

----
-layout: null
----
-<?xml version="1.0" encoding="UTF-8"?>
-<rss version="2.0" xmlns:atom="http://www.w3.org/2005/Atom">
-  <channel>
-    <title>{{ site.name | xml_escape }} - Articles</title>
-    <description>{% if site.description %}{{ site.description | xml_escape }}{% endif %}</description>
-    <link>
-    {{ site.url }}</link>
-    {% for post in site.posts %}
-      {% unless post.link %}
-      <item>
-        <title>{{ post.title | xml_escape }}</title>
-        {% if post.excerpt %}
-          <description>{{ post.excerpt | xml_escape }}</description>
-        {% else %}
-          <description>{{ post.content | xml_escape }}</description>
-        {% endif %}
-        <pubDate>{{ post.date | date: "%a, %d %b %Y %H:%M:%S %z" }}</pubDate>
-        <link>
-        {{ site.url }}{{ post.url }}</link>
-        <guid isPermaLink="true">{{ site.url }}{{ post.url }}</guid>
-      </item>
-      {% endunless %}
-    {% endfor %}
-  </channel>
-</rss>

[Link](url) and 

