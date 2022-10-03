# Embedding Images with GitHub Markdown

***

GitHub Markdown has several options for embedding images. One of the most straight forward is using Markdown version of the image embed:

![UBC Logo](https://brand3.sites.olt.ubc.ca/files/2018/09/5NarrowLogo_ex_768.png "UBC Logo")
Logo link: https://brand3.sites.olt.ubc.ca/files/2018/09/5NarrowLogo_ex_768.png

# Adding YouTube Videos
***
They can't be added directly but you can add an image with a link to the video like this:
```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=of19I4LsFh8
" target="_blank"><img src="http://img.youtube.com/vi/of19I4LsFh8/0.jpg"
alt="Welcome to UBC's Okanagan campus" width="240" height="180" border="10" /></a>
```
Or, in pure Markdown,but losing the image and border:
```
[![Welcome to UBC's Okanagan campus](https://www.youtube.com/watch?v=ofl9I4LsFh8)](https://www.youtube.com/watch?v=ofl9I4LsFh8)
```
Click on the image to play the video:
[![Welcome to UBC's Okanagan campus](https://www.youtube.com/watch?v=ofl9I4LsFh8)](https://www.youtube.com/watch?v=ofl9I4LsFh8)








