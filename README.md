# JavaScript Tetris

Open `index.html` in a current browser with JavaScript and 2D canvas support. The game runs offline and requires no installation or build. It includes Hold and Next previews, levels, line-clear effects, touch controls, and a browser-local high score. If the browser blocks storage, the record lasts until you close or reload the page.

## Controls

| Key | Action |
| --- | --- |
| Enter or Space | Start a game |
| Left and Right arrows | Move |
| Up arrow | Rotate |
| Down arrow | Soft drop |
| Space during play | Hard drop |
| C | Hold or swap a piece |
| P | Pause or resume |
| Esc | End the game |

On phones and tablets, the on-screen buttons also let you pause, resume, and end the game. Open **Text view of the board** for the active piece, landing cells, held and next pieces, and occupied cells by row. Pause to inspect a stable board.

## Standalone assets

`stats.js` is an optional performance monitor. To use it on another page, load it as a classic script, create `new Stats()`, append its `domElement`, and call `update()` once per animation frame. `texture.jpg` is an optional background image that can be referenced from CSS with `url(texture.jpg)`. The game page uses its own CSS and does not load either asset.

## Upstream and license

The original project has a [demo](https://jakesgordon.com/games/tetris/), [design article](https://jakesgordon.com/writing/javascript-tetris/), and [source repository](https://github.com/jakesgordon/javascript-tetris). The project code uses the [MIT license](LICENSE). The bundled Bungee font uses the [SIL Open Font License](assets/bungee-OFL.txt).
