# Terminate
---
#### Syntax theme for the Atom.io editor

> See snapshots below to see what Terminate looks like

An adaptation of Apple's green default Terminal settings with a touch of blues, yellows and red to contrast important syntax like function calls, constants, strings, operators and comments while keeping a central color scheme.

#### LESS (here is a screenshot of Terminate's color scheme)
![less](https://cloud.githubusercontent.com/assets/14797743/20460431/01afa88c-ae97-11e6-90e7-6658f1332fb9.png)
#### CSS
![css](https://cloud.githubusercontent.com/assets/14797743/20460432/01cdb23c-ae97-11e6-90d1-ffa20ddb10f0.png)
#### HTML
![html](https://cloud.githubusercontent.com/assets/14797743/20460451/68cf45a4-ae97-11e6-988b-06f029a231a8.png)
#### Markdown
![markdown](https://cloud.githubusercontent.com/assets/14797743/20460388/3e6aee8c-ae95-11e6-9e1b-31fdeae88da0.png)
#### Javascript
![javascript](https://cloud.githubusercontent.com/assets/14797743/20460387/3e6abf5c-ae95-11e6-8bcc-fb691b1f70e5.png)
#### Ruby
![ruby](https://cloud.githubusercontent.com/assets/14797743/20460390/3e734f50-ae95-11e6-8685-a7dd8fc192b3.png)
#### Python
![python](https://cloud.githubusercontent.com/assets/14797743/20460389/3e6cfa24-ae95-11e6-9ff0-c4f71e90ff98.png)
#### Elixir
![elixir](https://cloud.githubusercontent.com/assets/14797743/20460386/3e68a9ce-ae95-11e6-9c12-45847b78d62d.png)

## Idea behind Terminate:
- Old school feel of bright green font with a dark background.
- Contrasting colors to allow important operations/code to 'pop out' from the dark background and other code that isn't as important.
 - Comments are dark and closely colored to the background to remove their importance of interpreted code
 - Function calls are brightened to show where in your code they're being called at
 - Constants are bright red and important operations (arithmetic and comparisons) are dark red
 - Strings are very light hue of the main green font color. This color is near opposite of comments and are easily seen.
- Syntax UI to fit any language (see below for language support)
- Search results are outlined in bright red

## Color Scheme
- Main text color- lime green
- Background color- dark teal (near black)
- Supporting colors- dark green, pale lime, teal and blue
- Comment color- lightened shade of background color
- String color- bright white shade of main text color
- Constants and operations color- from dark to normal red

## Language Support
**Terminate** *should* display nicely with most common languages. If not open an issue and I'll fix it (I'm also open to pull-requests. See below for more information). I've tested Terminate with the following languages:
- Markdown
- HTML &amp; CSS (LESS, SASS)
- Python
- Ruby
- Javascript &amp; JSON
- Elixir

## Pull Requests
Gladly accepting pull-requests. First open an issue if one hasn't been opened already and let's discuss changes. I'd like help to work with other languages that I am not familiar. Those would be any languages I have not supported above. Thank you!

## Todo:
- edit any `@red` attributes- I did this to note that I need to fix these. So in a language if there is an odd red syntax it's probably an attribute that hasn't been intentionally set yet.
- Language-specific
  - HTML-
    - make color of `class` attributes match `id`
    - make all `href` attributes same color
    - make all `=` same color
  - Python
    - fix color for constants and booleans. Not showing highlighted as red
  - Ruby-
    - fix color of function calls. Not showing as highlighted neon-green
    - fix color change of interpolated strings
  - Elixir-
    - fix color of constants
    - change single line `do`'s to secondary color (teal)
