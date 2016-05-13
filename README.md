# robhinds.github.io
A Jekyll based CV page generator based on the user profile page on Nerdability.

You can checkout the page generated for this repo here: http://robhinds.github.io

A few years agao I helped create a devloper CV webapp that let users sign up and connect lots of online footprints to make a dynamic online CV (formerly nerdability.com, now parked at: http://nerdability.esy.es/ ), and I thought why not just create a static site generated version that re-created the user profile CV.  Luckily, GitHub provides native support for Jekyll sites as part of its user pages (http://{{yourusername}}.github.io), so as well as hosting the Jekyll project on GitHub, it also automatically builds and serves the site for you on a nice share-able URL.


## Making your own CV

To make your own GitHub hosted CV:

1. Fork this repo into your github account 
2. Click the "Settings" button in your new forked repository (in the menu on the right), and change the repository's name to {{yourusername}}.github.io, replacing yourusername with your GitHub user name.
3. Update /_config.yml with the details of your CV - the comments will explain what is required
4. Visit http://{{yourusername}}.github.io to check it out
5. Share your new CV/Profile with the world!


If you want to test it locally, install Ruby & Jekyll, clone the repository locally and run "jekyll serve" from the repo root directoy.

If you want to host the page on your own web hosting, you will need to run it locally and jekyll will build the site files to the /_site directory which you can then push to your hosting provider - See https://jekyllrb.com/ for details.


