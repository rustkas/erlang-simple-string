Erlang simple string
====================

A wrapper library that attempts to make Erlang's string functions in the string, lists, erlang, and (eventually) re modules seem coherent to beginners.

The initial version is purely a wrapper for traditional list-based strings.  Future versions may:

* rename some functions to make them more familiar to developers coming from other languages
* fill some gaps for string functionality
* add support for binary strings across the set

The library is under the (2-clause) Simplified BSD license.

------------------------


Build
-----
	$ rebar3 compile

Run EUnit tests
-----
	$ rebar3 eunit -v
	
Format
-----
	$ rebar3 format

Generate documentation
-----
	$ rebar3 edoc
