

# ~~Phœnix Dark~~ 
## There's a newer (BETTER!) version:
- Extension: https://marketplace.visualstudio.com/items?itemName=ncodefun.simple-focus-web
- Repo: https://github.com/ncodefun/simple-focus-web

## VS Code theme with a minimal color palette, focused on values 

Successor of the 'simple-focus' theme, with a more uniform color palette.

- All value types have the same vivid color;
- Colors for keywords / control characters / ponctuation etc. are muted;
- Optimised to work with the lit-html extension (js in html in js...).

HTML colors are different / contrasting with JS colors so when both languages are mixed in string template literals they are clearly distinct.

### Javascript, Javascript + HTML (lit-html)

![js demo](./screenshots/javascript.png)

Almost there: note that in the last example the deepest div is not correctly highlighted as HTML, but as a normal string. Not sure whether this depends on the lit-html extension or the language services... Hopefully this should be adressed soon!

### HTML / PUG

![html screenshot](./screenshots/html.png)

![pug screenshot](./screenshots/pug.png)

### CSS

![css screenshot](./screenshots/css.png)
