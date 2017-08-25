# readMore
jQuery plugin that cuts text at required length and replace the rest with "... Read More" link, redirecting to the full article.

* Easily customizable
* Pretty lightweight
* Doesn't rely on external libraries (besides jQuery)

## How to use:

Make sure to include jQuery in your page:

```html
<script
  src="https://code.jquery.com/jquery-3.2.1.min.js"
  integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4="
  crossorigin="anonymous"></script>
```

Include **jQuery readMore:**

```html
<script src="js/readMore.jquery.js"></script>
```

## Function call:

using jQuery selector select the property you want to apply the readMore fn. Define the max numberOfLines that are required for your needs throught key - value

### Example

$(".element").readMore({numberOfLines: 5});


## Browser support:

* Firefox (v 45 +)
* Chrome
* Safari
* Internet Explorer 7+
* Safari
