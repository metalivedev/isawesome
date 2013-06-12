isawesome
=========

What if everything they said about Chuck Norris was about you instead?
How awesome would that be?

Try pushing this dotCloud example to your own dotCloud service.
When you've read how awesome Hipache is, you can switch to your own name.
Just add ``?AWESOME=(your name)`` to the URL once, and the service will make you The Norris.

Actually, this is just a ridiculous example of simple Nginx configuration for cookies and proxies.
Apologies to www.chucknorrisfacts.com for abusing their awesomeness.

Depends on nginx sub_filter module, which you must compile-in explicitly.
See http://wiki.nginx.org/HttpSubModule#sub_filter for information about the filter, 
and the [top of that page](http://wiki.nginx.org/HttpSubModule) for instructions on how to include the module in the configuration.
**HttpSubModule is not included by default** (see list of [optional NGinx modules](http://wiki.nginx.org/Modules#Optional_HTTP_modules) 
where it is listed as `Substitution`.)
