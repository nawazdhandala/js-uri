js-uri <http://code.google.com/p/js-uri/>
=========================================

This is a small JavaScript library for manipulating URIs.  It parses, recreates and resolves them.  For example:

  var some_uri = new URI("http://www.example.com/foo/bar");

  alert(some_uri.authority); // www.example.com
  alert(some_uri);           // http://www.example.com/foo/bar

  var blah      = new URI("blah");
  var blah_full = blah.resolve(some_uri);
  alert(blah_full);         // http://www.example.com/foo/blah

It is based around code in RFC3986, "Uniform Resource Identifier (URI): Generic Syntax".

@(#) $Id$