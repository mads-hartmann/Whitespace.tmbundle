TextMate bundle for whitespace 
==============================

So far it has two grammars it injects into all other scopes. It adds the scopes invalid.illegal.whitespace.trailing to all trailing whitespace and invalid.illegal.whitespace.mixed to all occurrences of mixed spaces/tabs. This means you can spot all your whitespace hiccups before Git does. 

**Author**: Mads Hartmann Jensen

Install
-------

If you have git, you can install cloning the repository to your user library folder:

    mkdir -p ~/Library/Application\ Support/Avian/Bundles
	cd ~/Library/Application\ Support/Avian/Bundles
    git clone https://github.com/mads379/Whitespace.tmbundle.git

If you don't have git, you can download it (using the zip button in the bar), extract the zipfile and copy the extracted folder to `~/Library/Application Support/Avian/Bundles`.
