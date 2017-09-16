# Three.js Tutorial Standards

A set of recommended standards for tutorials covering techniques in Three.js. These standards aim to improve the developer experience for newcomers who are unfamiliar with WebGL and Three.js.

## The Context

Three.js is a rapidly developing library. The maintainers are releasing new versions regularly and the features available are changing drasticly. 

At the same time the web industry is experiencing growing demand for 3D graphics in browser and as a result, many web developers are adopting the Three.js framework for the first time. 

## The Problem

It is not immediately obvious to a newcomer how different the code inside the Three.js library is between versions. It is not even obvious that multiple versions exist as they are called "Revisions" in Three.js and often refered to in the short hand "r59". Many introduction articles fail to explain this. 

Unlike other popular JavaScript libraries like jQuery which has the version number in the file name _(eg jquery-3.2.1.min.js)_, Three.js is almost always saved as _three.js.min_, promoting the illusion that version is of minimal importance.

There is not a huge number of people publishing content about Three.js but there are numerous subjects to tackle. Therefore, out-dated tutorials are sticking around near the top of the search results many years after they have become misleading. It is often not until you reach the user comments section at the bottom that you see the code in the example is broken in newer versions. By this point you may have wasted a lot of time trying to make it work. 

These misleading articles frustrate and confuse newcomers, ruining the developer experience during those critical first hours and that will damage the reputation of what is an excellent library!

## Solution

Transparency around version (revision) number needs to be much more prevalent. 

 - _"Introduction to Three.js"_ style articles should set out to educate newcomers about how important it is to be conscious of which revision you are using
 - _"How to [something] in Three.js"_ style articles should always start with a comma-separated list of the version numbers that this code is known to work in. This will free publishers from having to go back and edit old posts.
 
## History of releases

Here's a guide to which version Three.js a post is likely to have been based on, dependant on when it was published. 

 - 2011: r33 - r46
 - 2012: r47 - r54
 - 2013: r55 - r64
 - 2014: r65 - r69
 - 2015: r70 - r73
 - 2016: r74 - r83
 - 2017: r84 - r87

## Examples

If you search by the term _"how to make object cast shadow in three.js"_ you will most likely end up at this blog post from 2012 http://learningthreejs.com/blog/2012/01/20/casting-shadows/  Some of the code in this tutorial doesn't just "not work" or throw an error in newer versions, it silently breaks the shadow map, forcing the developer into a pit of confusion.
