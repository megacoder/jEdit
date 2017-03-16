# jEdit
My clone of the https://sourceforge.net/p/jedit/svn/HEAD/tree/jEdit/trunk/ SVN repository

## How This Repo Was Made

	$ # Make a working directory to hold the SVN checkout
	$ mkdir jEdit-svn
	$ svn checkout https://sourceforge.net/p/jedit/svn/HEAD/tree/jEdit/trunk/
	$ # Create the GIT repo on github.com and then:
	$ git clone https://github.com/megacoder/jEdit
	$ # Import the SVN download
	$ cd jEdit
	$ cp -rl ../jEdit-svn/. .
	$ git add -A ./
	$ git commit -a -m 'Original import'
	$ git push

## README

The original compilation instructions are in the:

	README.SRC.txt

file.
