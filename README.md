# Widths

The aleutcss `widths` module is a simple file of helper classes to drop widths
onto elements such as grid systems.



Install using npm:

    $ npm install --save-dev aleut-widths

aleutcss’ widths classes are available in one of two formats. The default format
is fraction-like, e.g.: `<div class="u-1/2">`.

The other available format is spoken-word, e.g. `<div class="u-1-of-2">`.
Enable this by predefining the `$inuit-use-fractions` feature switch, e.g.:

    $inuit-use-fractions:    false;
    @import "path/to/trumps.widths";
