# Slides for a presentation about Docker, in Docker!

Slides are presented using [remark](http://remarkjs.com/) via
[markdown-to-slides](https://www.npmjs.com/package/markdown-to-slides).

To build and run the slides, use one of the helper scripts:
- `./scripts/build-and-run` will output a static HTML file, serve it with a
  web server, and open it in a browser.
- `./scripts/live-build-and-run` uses markdown-to-slides's `--watch` mode to
  automatically rebuild the presentation when slide content changes. You just
  need to refresh the browser page.

## To use presenter mode:

1. Run the presentation.
1. Press "c" to open a new window for the actual presentation.
1. Focus the original window again, then press "p" to enter presenter mode.

The two windows will remain in sync, so you can show one to the audience and
the other to yourself.
