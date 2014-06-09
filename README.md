# Demo

[View demo](http://artsy.github.io/artsy-iconfont/output/demo.html)

# Editing the icon font

## Preparing artwork

A template for a 32x32px grid can be found in the directory `templates`.

In Illustrator: turn on `View > Show Grid` and `View > Snap to Grid`. Guides are placed to form a 20x20px box at the center of the template. The majority of the icons sit within this box. Aim to have points terminate at complete pixel values whenever possible.

A script for exporting all open documents to SVGs is include in the root directory (`SVGs.jsx`).

## Managing the font

The font itself is currently managed through the service http://icomoon.io.

* Go to [http://icomoon.io](http://icomoon.io)
* Click the purple "Import Icons" and select the output/selection.json file from the root of this project.
* Click the "arty-icons" set hamburger menu and select "Import to Set"
* Click the hamburger menu again and select "Select All" to highlight all of the icons
* Click through to 'Font', edit any of the names and 'Download'
  * This will provide you with a `.zip` file containing the font files (`.eot`, `.svg`, `.ttf`, `.woff`) and CSS
  * Replace the contents of `/output` with the contents of the `.zip`

There is most definitely room for improvement in this workflow; suggestions welcome.
