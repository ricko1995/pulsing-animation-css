# Pulsing Animation with CSS

Simple pulsing animation using CSS custom properties.

![Preview gif](https://github.com/ricko1995/pulsing-animation-css/blob/master/preview.gif?raw=true)

## Usage:

Download and link css https://github.com/ricko1995/pulsing-animation-css/blob/master/pulsing-anim-stylesheet.css :

```html
<link rel="stylesheet" href="pulsing-anim-stylesheet.css" />
```

Create pulsing-container with pulsing-icon:

```html
<div class="pulsing-container">
	<div class="pulsing-icon">&#9763;</div>
</div>
```

Some properties can be changed using css custom properties on pulsing-container:

```css
--background-hue: 230;
--icon-size: 6rem;
--font-size: 6rem;
--pulse-duration: 3s;
```

Example:

```html
<div class="pulsing-container" style="--background-hue: 130; --font-size: 54px; --icon-size: 54px; --pulse-duration: 1s">
	<div class="pulsing-icon">&#9763;</div>
</div>
```
