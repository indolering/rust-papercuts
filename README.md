# Rusty Paper Cuts

Notes on difficulties learning rust, in the form of a usability test.  I'll eventually rework this to mark things that newbies wouldn't know....

## Day 1

### Finding Resources
The list of Rust learning resources is a grab-bag of content, without much integration between sources [#1](https://github.com/indolering/rust-papercuts/issues/1).  

Okay, looks like [Exercism](https://exercism.io/my/tracks/rust) has a free course with mentoring!  *A few hours later:* Nope, that was a lie!  It's just a bunch of almost mechanically translated excericises, the mentoring program is overloaded, and the site is actually [restructuring everything](https://exercism.io/blog/sorry-for-the-wait).

Well, let's at least try to get everything installed and ready to go.

### Install

Seriously, I have to run a random f*cking bash script directly off of the internet?  Oh, it's in Ubuntu's package manager ... but Rust ships a new version every six weeks (!) and I don't want to have issues with using a non-standard installation.  Can't they just provide a .deb or .rpm package of stable ([no](https://github.com/rust-lang/rustup/issues/800))?  Oh, okay, they provide signed binaries in the alternate installation methods.  *Sigh* so if I want even the bare minimum of security I either have to give up on running stable or put in a lot of manual labor.

/me *adds creating secure rust installation via Ansible to TODO list.*

### IDE Setup
Boy, the website sure is useless in choosing an IDE.  Good thing I know about [areweideyet.com](https://areweideyet.com/).  Only Eclipse, VSCode, and Intellij support debugging.  VSCode is the favorite in the [Rust Survey](https://blog.rust-lang.org/2020/04/17/Rust-survey-2019.html), Eclipse never impresses me, and Intellij costs lots of money.

Rust Analyzer seems to get all of the focus when it comes to improving the development experience, but **boy** is everything else confusing and craptastic here:

* The extension pack doesn't really cover everything and the snippets are anemic.  I swith between Java, JS, PHP, and Haxe regularly.  How am I supposed to remember all this syntax?
* How do I get Rust Analyzer working?  Is it better than the existing RLS?
* Debugging is a nightmare.
