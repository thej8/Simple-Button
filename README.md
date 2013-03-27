#Simple-Button


Full CSS3 Button

## Quick Start

Include the css file into your directory.

```
<link rel="stylesheet" href="button.css">

```

to create a new button : 

```
<a href="#" class="btn">Your text</a>
```

## Color

By default there are 6 colors button.

```
<a href="#" class="btn">Default</a>
<a href="#" class="btn white">White</a>
<a href="#" class="btn red">Red</a>
<a href="#" class="btn blue">Blue</a>
<a href="#" class="btn orange">Orange</a>
<a href="#" class="btn turquoise">Turquoise</a>
<a href="#" class="btn green">Green</a>
```

## Rounded

For rounded buttons:

```
<a href="#" class="btn-round">Rounded</a>
```

You can also change the color of rounded buttons.

```
<a href="#" class="btn-round white">Rounded</a>
<a href="#" class="btn-round red">Rounded</a>
…
```

## Square

For rounded buttons:

```
<a href="#" class="btn-square">Rounded</a>
```

You can also change the color of square buttons.

```
<a href="#" class="btn-square white">Rounded</a>
<a href="#" class="btn-square red">Rounded</a>
…
```

## Size

There are three sizes of buttons

```
<a href="#" class="btn small">Small</a>
<a href="#" class="btn">Default</a>
<a href="#" class="btn huge">Huge</a>
```

## Icons

Buttons with icons (with icons by [font-awesome](http://fortawesome.github.com/Font-Awesome/)) :

```
<a href="#" class="btn-square ico"><i class="icon-{name}"></i><span>Your text</span></a>
```

You can also change the color, make square or rounded icons buttons.

## Social

Buttons "social" for facebook and twitter (with icons by [font-awesome](http://fortawesome.github.com/Font-Awesome/)) : 

```
<a href="#" class="btn fb"><i class="icon-facebook"></i><span>facebook</span></a>
<a href="#" class="btn tw"><i class="icon-twitter"></i><span>twitter</span></a>
```

## {LESS} and MIXIN

You can easily add a color button through MIXIN with {LESS}.

```
[class*='btn'].blue {
  .button (#color);
}
```

## Credits

* Code and design by JBLemaire
* Icons By [Font-Awesome](http://fortawesome.github.com/Font-Awesome/)
* <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.fr" style="border: none;"><img alt="Licence Creative Commons" style="border-width:0; vertical-align: middle;" src="http://i.creativecommons.org/l/by/3.0/80x15.png" /></a> <a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.fr">Licence Creative Commons Attribution
