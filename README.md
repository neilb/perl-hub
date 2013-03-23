This is a proof-of-concept for a central "perl community hub" - a single place where all perl people can come to find out what's going on in the perl world. The basic idea is

 * you would log in, using your PAUSE id, twitter, facebook, etc
 * you could configure what you'd see on the front page
 * you would provide details of your blog, any talks you've given, links to perl resources you've found

This is just a mashup, built with the build-hub script. This does the following

 * reads the list of perl blogs from conf/blogs.json
 * reads the list of upcoming events conf/events.json
 * reads the list of talks from conf/talks.json
 * reads the list of links to perl resources from conf/links.json

It also grabs various perl related feeds, in some cases munges them, and maps them into the feeds
at the bottom of the page.

If you want to add your blog, details of talks you've given, or any links I've missed,
either send me a pull request, or raise an issue on github.

You can read more about the idea on my [blog post](http://blogs.perl.org/users/neilb/2013/03/idea-perl-community-homepage.html)

