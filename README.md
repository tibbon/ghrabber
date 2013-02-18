Grab all files matching a search specification from Github. 

Downloaded files are written to files named user.repository. Existing files
with the same name are skipped, which means that you can reasonably efficiently
stop and resume a ghrab. 

Note that this is a Quick Hack that may break whenever Github changes even
minor features on the site.


### Examples


    ghrabber.py "path:.bash_history"

    ghrabber.py "extension:key"