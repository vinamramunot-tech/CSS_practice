<h1>CSS Practice with Scrimba</h1>

<h2>Transition</h2>

**All done using hover property**

<h3>Adding Transitions</h3>

>transition "specific value we want to transition" "time it takes to transition in seconds"

<p align="center">An example of css code is given below</p>

```css
.heading {
color: blue;
font-size: 20px;
transition: color 0.5s;
}
```

Here if we want target different properties together we can separate properties by comma or all the properties together

>transition "specific value" "time in sec", "specific value" "time in sec", "more properties" "time in sec"

>transition all "time in sec"


<p align="center">An example of css code is given below</p>

```css
.heading {
color: blue;
font-size: 20px;
//transition: color 0.5s, font-size 1s;
//transition: all 0.5s;
}
```

<h3>Customization transition</h3>

1. Transition Delay
This will add a pause for 1s second before the transition occurs.
```css
.heading {
    //...
    transition-delay: 1s;
    //...
}
```

2. Separating properties within transitio
```css
.heading {
    //...
    transition-property: color, font-size, all;
    transition-duration: 1s;
    //...
}
```

3. Transition timing function
```css
.heading {
    //...
    //transition-timing-function: ease;
    //transition-timing-function: linear;
    //...
}
```

<h3>Transition Shorthand</h3>

>transition "transition-property" "transition-duration" "transition-timing-function" "transition-delay"

```css
.heading {
    //...
    transition: font-size 0.5s ease-in 1s;
    //...
}
```

## Animation

standalone, not dependent on pseudo classes

setting two things in the parent css block:
`animation-name` : `grow`;
`animation-duration` : `2s`;

```css
@keyframes "name of the animation" {
    /*
    from {all the properties}
    to {all the properties}
    */

    /* setting up different percentage of growth
    0% {}
    50% {}
    100% {}
    */

    from {width: 100px; height: 200px; background: red}
    to {width: 20px; height: 20px; background: blue}

}





> A Link to markdown cheatsheet [ME][1]



[1]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet