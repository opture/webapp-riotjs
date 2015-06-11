# webapp-riotjs

## A repository to clone for riotjs based projects.

This uses a directory strucutre for tags
<pre>
app
 |- tags
      |-elements
      |        |- element-tag
      |                     |- tag-name.tag
      |                     |- tag-name.scss
      |-pages
      |     |-tag-name
      |              |- tag-name.tag
      |              |- tag-name.scss      
</pre>

Grunt tasks are added that concatenates all the scss files from elements and pages directories before runnings the ordinary webapp tasks.
