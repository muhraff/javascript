# Javascript examples and snippets



## Get Video Thumbnail ID form Vimeo video page



```js
javascript:if(/^https?:\/\/vimeo\.com\/\d+/.test(window.location.href)){ var url = document.querySelectorAll('.vp-preview.vp-preview-cover')[0].dataset.thumb; alert('Video Thumbnail ID: '+ /video\/(\d+)/.exec( url )[1]);}else{ alert('OOPS! \nYour are not Vimeo video page') }
```
