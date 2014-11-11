elemental
=========

Composition calculator for chemicals.  For use in lab work and workup from lab work (see below for features)

Features
========
* Mass spectrum prediction for the [M]+ ion#
  * includes isotopic data from 1997 composition information
  * data can be seen to check used amounts
  * where an element is radioactive, or no known isotopic data exists, then [M]+ cannot be calculated
* predicted elemental composition
* elemental analysis from experimental results
* determining needed chemical amounts for filling in COSSH forms
* works offline in the browser.  No internet connection is required.  
* No information is ever sent out, apart from google analytics information, which helps me to work out where people are from, and what screen sizes people are using so that I can work on this more effectively
 
To use
======
Simply point your browser at the [public file on git](http://sgazard.github.io/elemental/)  Or, save it to your computer.  Modern browsers will need only to save one file, making it easier to move around once saved

Why it was built
================
Simply, I needed it in 2008 during my PHD.  It's been available online, but I wanted to improve the code (certain parts are in dire need of improvement), make it cleaner, and improve performance where possible, as a few bottlenecks exist.

What you Won't see here
=======================
Angular, backbone, or any other framework.

Why?  Well, when it was built, the intention was that you could take it as a web app with you to any computer, anywhere, meaning you might not have an internet connection.  Despite the advances in connectivity, many parts of the world are without ubiquitous, cheap internet connections.  I was at a university with a very high speed connection (think multiple 10Gbps fibre connections), and not all computers connected to instruments had an internet connection, so offline access to this is very useful.  While writing my thesis, I was in countries where power was only around for 4 hours/day (if I were lucky), and data access was even more spotty so it's intentional to have this version working without frameworks and run on a very simple subset of Javascript that requires very little technical knowledge.

What you can do
===============
Use it.  If you need it offline, copy it to your computer and use it on the road, anywhere.  You could be using it on a plane flight or in the middle of the desert, or even under the ocean!
