# Jake & Elwood

Here are the specs:

The Adobe XD [link](https://xd.adobe.com/spec/f255d364-6d5e-4aaf-7703-6f8d0a398281-8464/grid/) for all of the pages.

And the condensed version for the Home page.

![](https://raw.githubusercontent.com/hoc-labs/images/main/rdb-jake-img1.png)

The starter HTML file already has the necessary includes for the required font as well as the font-awesome CDN.

Here are the font-awesome icons we will be using. Just insert them in your markup where you want them to appear.

### Background Images

These are the properties that you will need to use for the background image

* background-image
* background-position
* background-size

### Using Font-awesome Icons

This is how you add a font-awesome icon to your markup.
```html
<i class="fab fa-facebook-square"></i>
<i class="fab fa-twitter"></i>
<i class="fab fa-instagram"></i>
```

### Pseudo-element

This is how you add the pseudo-element to create an underline.

```css
.section-title::after {
    content: "";
    display: block;
    width: 60px;
    height: 3px;
    margin-top: 10px;
    background: #FFE600;
    margin-left: auto;
    margin-right: auto;
}
```
