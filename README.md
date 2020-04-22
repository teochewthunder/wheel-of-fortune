# Wheel Of Fortune
Not strictly the game show's version. Basically, click and drag across the screen. The wheel spins more or less depending on ow long the drag was.

## The Wheel
HTML and CSS. This uses two rectangular divs (with the `overflow` property set to `hidden`) within a square div, and six differently colored and rotated divs (segments) within each rectangular div.

Note that this does not work in Safari and a rather clumsy fix is in the Safari branch.

## JavaScript
Uses an array to store the "prizes". A `mouseup` and `mousedown` event tracker detects mouse activity, and tracks the position of the mouse to determine how far it has travelled from point A to point B. The greater the distance, the more the wheel spins within ten seconds, will it slows to a halt.
