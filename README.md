# CSS3 Buttons #

## What is this? ##

[CSS3 buttons](http://css3buttons.michaelhenriksen.dk) is a simple *framework* for creating good-looking GitHub style button links.

## Buttons ##

To create a button, the only thing you have to do is this:

    <a href="#" class="button">This is a Button</a>

You can also use the button tag:

    <button class="button">This is a Button</button>

If you prefer a pill-like button with more rounded corners, you can add a `.pill` class to the button

    <a href="#" class="pill button">This is a Pill Button</a>

Sometimes when you have multiple buttons, it's a good thing to highlight the button with the primary action 
in order to give the user a visual clue of what action to take if in doubt. This can be accomplished by adding 
a `.primary` class to the button

    <a href="#" class="primary button">Publish Post</a> or <a href="#" class="button">Save as Draft</a>

## Buttons with negative actions ##

If you have a button that triggers a negative action, like deleting data, it's good practice to warn the user 
by styling the button differently than the normal buttons. Give a button the class `.negative` and the 
hover-state will change to red

    <a href="#" class="negative button">Divide by Zero</a>

## Buttons with positive actions ##

If you have a button that triggers an action you want to encourage your users to do, you can give a button a `.positive` class and the hover-state will change to green

    <a href="#" class="positive button">Save the World</a>

## Grouped buttons ##

You can create grouped buttons that are linked together, like seen at Gmail and other places, 
by using the `.left`, `.middle` and `.right` classes:

    <a href="#" class="left primary button">Archive</a>
    <a href="#" class="middle button">Report Spam</a>
    <a href="#" class="right negative button">Delete</a>

You can also add the pill class to grouped buttons if preferred:

    <a href="#" class="left primary pill button">Archive</a>
    <a href="#" class="middle pill button">Report Spam</a>
    <a href="#" class="right negative pill button">Delete</a>

## Buttons with icons ##

CSS3 Buttons supports a wide range of icons that can easily be added to any button by adding a span tag inside the anchor 
tag with the class of `.icon` and any one of the provided icon classes:
)
    <a href="#" class="button"><span class="magnifier icon"></span>Search</a>

Here is a list of all the supported icon classes:

 * `.book`
 * `.calendar`
 * `.chat`
 * `.check`
 * `.clock`
 * `.cog`
 * `.comment`
 * `.cross`
 * `.downarrow`
 * `.fork`
 * `.heart`
 * `.home`
 * `.key`
 * `.leftarrow`
 * `.lock`
 * `.loop`
 * `.magnifier`
 * `.mail`
 * `.move`
 * `.pen`
 * `.pin`
 * `.plus`
 * `.reload`
 * `.rightarrow`
 * `.rss`
 * `.tag`
 * `.trash`
 * `.unlock`
 * `.uparrow`
 * `.user`

## Big buttons ##

If you wish to emphasize a specific action you can add the `.big` class to make a more prominent *call-to-action* button:

    <a href="#" class="big button">Create Project</a>

## Browser compatibility ##

CSS3 Buttons works in all major browsers

**Note:** Some CSS3 features used in CSS3 Buttons is not supported in Internet Explorer browsers! (IE 8 and under)

## Installation ##

 1. Drop `css3buttons.css` in your stylesheets folder
 2. Drop `css3buttons_backgrounds.png` and `css3buttons_icons.png` in your images folder
 3. Link to `css3buttons.css` in the head section of your HTML page

## License ##

### The [Unlicense](http://unlicense.org): ###

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

In jurisdictions that recognize copyright laws, the author or authors of this software dedicate any and all copyright interest in the software to the public domain. We make this dedication for the benefit of the public at large and to the detriment of our heirs and successors. We intend this dedication to be an overt act of relinquishment in perpetuity of all present and future rights to this software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>

## Shout-Outs ##

 * Thanks to [GitHub](http://github.com) and [David Walsh](http://davidwalsh.name/github-css) for inspiration!
 * Icons used in CSS3 Buttons are from the excellent [Iconic pack](http://somerandomdude.com/projects/iconic/) by [some random dude](http://somerandomdude.com/)!

## Contact ##

### Found a Bug? ###
Please create a [ticket on GitHub](https://github.com/michenriksen/css3buttons/issues) With a description of the problem, browser and operating system information and how to reproduce the problem.

### Need Help? ###
You can send me a private message on [GitHub](http://github.com/michenriksen/) and I'll do my best to help you.
