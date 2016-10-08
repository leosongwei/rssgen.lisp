rssgen.lisp
===========

I use this script for generating the RSS feed and the article list in README.md in my [blog](https://github.com/leosongwei/blog/blob/master/README.md).

It's like JekyII or Hugo, generating a static 'website' hosting blog. The difference is, it build markdown files for blog hosted by a simple Github repo, not html hosted by a web server.

For manual, please refer to my blog and see how it works and read the source code. (There is no manual)

All I want is to keep it simple, so it can be short as the configuration file of others. Therefore, I won't introduce things like config files. If you want use this script, you are on your own.

Dependence
----------

This script is only build for SBCL, if you want to use other implementations of Common Lisp, you will have to adapt it by yourself.

Depend on:

* QuickLisp
	- s-xml
		- generate RSS xml
	- cl-ppcre
		- various usage
* pandoc
	- compile markdown into html
