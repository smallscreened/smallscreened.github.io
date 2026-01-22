--------------------------------------------------------------------------
title      : Small Screen
subtitle   : Testing In Progress
nav-group  : featured, new-3, tags, months
nav-width  : 320px
css-header : background:linear-gradient(to bottom right, #06c, #fc0); color:white
menu       : 
   Home    : ?
   Github  : https://github.com/smallscreened/smallscreened.github.io
   Dark    : javascript:darkmode()
   About   : ?page=about.md
--------------------------------------------------------------------------

<style comment="additional style">
#header { {{css-header}}  }
#left-panel  { width:{{nav-width}} }
#right-panel { left: calc({{nav-width}} + 20px) }
h1 { border-bottom:1px dotted grey }
.nav-post a  { color: teal }
.nav-tag  a  { color: #06c }
.nav-month a { color: grey }
.post-date   { font-size:12px; font-weight:400; }
.post-title  { font-size:16px; color:#333 }
.post-tags   { left-margin:20px; padding:4px; font-size:10px; color:green; font-weight:400 }
</style>

<div id="md-post">

home page in markdown syntax...

## Archive

* yyyy/mm/dd: [Hello World](?post=hello-world.md)  { #test, #tag2 }
* yyyy/mm/dd: [Post Title](md file)  { #tag1, #tag2 }
...
* yyyy/mm/dd: [Post Title](md file)  { #tag1, #tag2 }

</div>