Sandbox
=======

This is a space for the openEHR community to test Git/github features, feel free to "fork" files and play around...

Some subdirectories have specific purposes:
- [/testfolder_one](/testfolder_one) fool around here
- [/pathology](/pathology) reserved for info, mindmaps etc for the experiments described in https://discourse.openehr.org/t/refreshing-archetypes-related-to-pathology-reporting/2393/78
- [/local](/local) the default direectory that [Archetype Designer](https://tools.openehr.org/designer/) saves to in a github repository (this is where archetypes and templates you creat will end up by default, they can later be mnually moved into subdirectories under /local (for example /local/pathology) and still be found and edited by Archetype designer.

# "forks"
A thing with Git/Github  is that YOU can dig in and modify ("fork") entire repositories into your own space  
if you have a (free) Github account.

Your private fork will be "connected" to the original files (visible in the network graph at
https://github.com/openEHR/Sandbox/network) and all or some of your changes can (fairly easily) 
be "pulled" into later versions of the original file repository or into somebody else's fork(s).

Forking and simple file editing can be done online via the Github web interface if you don't need 
local/offline editing.

Read more about forks in https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks

# "branches"
Each fork can have a number of "branches" see https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches

# GIT clients
There are now very nice simple clients available for Github
- Windows: http://windows.github.com/
- Mac: http://mac.github.com/
- Linux users will be competent enough to find what they need...

More help can be found via e.g. https://help.github.com/

The GIT clients create a local copy/fork of repositories (like this "Sandbox") on your computer, you can then
update add or remove files locally. Whenever you want to freeze a snapshot of your work, you commit locally and
it becomes a local "unsynced commit". Whenever you want to share your progress with others (or your other 
computers) you sync your changes over to your own github account (this can also be done using the client).

These above described local commits do not affect other peoples' work, so feel free to secure your work by 
committing and even syncing to Github often. Sync is bidirectional, but don't fear, your own fork will not
contain any scary incoming changes unless you have put them there yourself ;-)

If you want to suggest that your modifications (made available in your public github fork) should be taken into
the main/original openEHR project, then you issue a "pull request" and the rest is up to the repository admins
(Tom & Erik currently). Even when the admins are slow to respond and merge your work to some "official" fork,
your improvments can anyway easily be pulled in by others to their own forks (circumventing possible bottlenecks).

Please test, and have fun!
