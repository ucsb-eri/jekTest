# jekTest
JekyllTest site for testing push triggers and such in prep for deploying Caylor jekyll site.

To install required components on Mac OSX (example from 10.11.6), you have to work around
SIP, so this requires installing gems in someplace other than /usr/bin.  One typical location is
/usr/local/bin, but I want to keep those separate from homebrew packages (they're supposed to coexist fine, but want to minimize chances of conflict).  So on my system (10.11.6) the following seemed to work well:
``` sudo mkdir -p /opt/local/bin
 1841  sudo gem install -n /opt/local/bin compass
 1842  sudo gem install -n /opt/local/bin jekyll
 1843  sudo gem install -n /opt/local/bin thin
 1844  sudo gem install -n /opt/local/bin sinatra
```
 Once the above is done, make sure you add /opt/local/bin to your path.
