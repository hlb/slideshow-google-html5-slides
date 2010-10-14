## Slide Show (S9) Template Pack - Google HTML5 Rocks

It is a forked version from [geraldb/slideshow-google-html5-slides](http://github.com/geraldb/slideshow-google-html5-slides).

## Changes

* Use the [latest version of HTML5 presentation](http://studio.html5rocks.com/samples/slides/index.html)
* Use @header[:title] in first slide
* Support !SLIDE syntax, check examples/ for details
  * The rdiscount gem generates weird code, uninstall it and use maruku gem if you can

## Try It Yourself - How To Use the Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow -f http://github.com/hlb/slideshow-google-html5-slides/raw/master/g5.txt

To check if the new template got installed, use the `-l/--list` switch/command:

    $ slideshow -l

Listing something like:

    Installed templates include:
       g5.txt (/home/USERNAME/.slideshow/templates/g5/g5.txt)

Now you're ready to use it using the `-t/--template` switch. Example:

    $ slideshow -t g5.txt tutorial

That's it. 
