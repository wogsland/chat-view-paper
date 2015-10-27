### Polymer demo chat application

Demo chat application presented at [Polymer Summit 2015](https://www.youtube.com/watch?v=ZDjiUmx51y8).

# Setup #

Assuming you already have Node & Bower installed,

    bower install
    cp elements/threads.json .

And if you want it to run reasonably fast, you'll want to polybuild it:

    npm install -g polybuild
    polybuild index.html

You'll also need to have a host setup since things expect to hit the root.

*NB: This simple app doesn't write anything back to `threads.json`.*
