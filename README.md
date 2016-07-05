# svena-comp1950
#####Path Links need to be fixed
If the pictures don't work it's probably because ive been using local paths --> ie url("logo.png")
It might be that we need something like url("svena-comp1950/logo.png") for it to work on github?

#####Embedded CSS note
Also, the normalize.css is really really long, so I made it like this:
<style> ...normalize.css...</style>
<style>...our own style</style>
so we could fold up the nomalize part.
I'll be doing the same with our media queries
ie, one tag for each media query (we have two in total to keep things simple)
