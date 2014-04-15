Fluent::Plugin::Resolv, a plugin for [Fluentd](http://fluentd.org)
======================

Fluent plugin, IP address resolv and rewrite.


Installation
------------

Add this line to your application's Gemfile:

    gem 'fluent-plugin-resolv'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install fluent-plugin-resolv


Usage
-----

	<match hoge.foo>
	  type resolv
	</match>


Configuration
-------------

- key_name

  target key. default is `host`.

- add_prefix / remove_prefix

  remove_prefix: removes the string from a prefix of tag.

  add_prefix: prepend the string to a tag.

- hostname_key

  resolved hostname key. default value is same as key_name.

inside
------

using ruby Resolv.


TODO
----

any patches, fork and so on. welcome !


