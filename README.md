# source code for pfarrell.com website
# note, we need to use SSI to included boilerplate from the /fragment directory
# we are using MultiViews, which helps resolved references to a URI like /foo to /foo.shtml
# and we have a rewrite rule to allow explicit URI like /foo/index.html to be re-written as /foo/index.shtml to get SSI working