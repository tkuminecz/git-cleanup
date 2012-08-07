git-cleanup
===========

git-cleanup is a shell script for git which cleans up merged branches, optionally backing them up to a remote.

Installation:

`$ git clone git://github.com/tkuminecz/git-cleanup.git && cd git-cleanup && make`

Usage:

`$ git cleanup` Deletes merged branches

`$ git cleanup -b [remote_name]` Pushes merged branches to the given remote and then deletes them
