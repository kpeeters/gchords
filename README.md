GCHORDS
=======

a LaTeX package for typesetting guitar chord diagrams

by Kasper Peeters <kasper.peeters@phi-sci.com>

# Introduction

Guitar players often use a notation for chords that shows a part of
the fretboard, indicating in a graphical way which strings to press
and where. GCHORDS is a LaTeX package that draws these diagrams using
only LaTeX symbols (i.e. without using any postscript/pdf
specials). This is what it looks like: 

![sample chords](sample.png?raw=true "Sample chords")

There are many options to change the size, use numbered dots, combine
chords with lyrics and so on. See the manual for detailed
information. Available under the GNU General Public License.


# Description of files

The package consists of the following files:

* `gchords.sty`, the style file. 
* `ChangeLog` contains the list of changes.
* `gchords_doc.tex`, the documentation, also available as a pdf file
`gchords_doc.pdf`.
* `chordbox.tcl`, an optional TCL script by D.Lovell, to create chords
  interactively.
* `get2knowu.tex`, an example of how to typeset chords above lyrics
  (also available directly as a postscript file
  `get2knowu.pdf`). Thanks to Yotam Medini for contributing these
  examples.


# Other guitar chord typesetting software

If gchords is not what you are looking for, maybe one of these
programs can help:

* GuitarTeX
 
 Graphical tool in Perl/TK for creation of guitar song sheets and song
 books, including tablature and chord diagrams (the latter using
 postscript, will use gchords.sty in a future version).
 
* MUP
 
 This program reads a text file with the description of music and
 outputs a postscript file. It has guitar chords added as an option,
 but I guess you can use that feature separately too. Does of course
 not mix with TeX as nicely as gchords, but the output looks good.
 
 * guitar.sty
  
 In case you only want to typeset the names of chords over the
 lyrics, this package has several useful facilities.

* MuseScore
  
 A new graphical music score typesetter.




