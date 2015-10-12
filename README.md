# trainTimes

This is horrible, nasty code that I wrote in 2013. It produced the beautiful site at tomforth.co.uk/traintimes and it could be improved now.

My suggestion would be to rewrite it completely but make use of the examples in distortbatch.bat as a guide. These will run in any shell with very minor modifications and rely on imagemagick.

The Shepards distortion is what does the magic. It is extremely powerful and the parameters took a while to get it right. It transform any image by mapping any number of co-ordinates to new positions.

This produces the background images on the website, with the foreground animations written in Raphael.js (thus producing SVGs) showing each city being moved from its original co-ordinates to its new co-ordinates.

There are two important data matrices, created in Excel then exported using VBA (enjoy that) as javascript objects of travel times and distances between every pair of cities.

As I said, a rewrite is probably the best option but I reckon that with the idea and using distortbatch.bat file as a guide that could happen quite quickly.

Have fun and good luck!