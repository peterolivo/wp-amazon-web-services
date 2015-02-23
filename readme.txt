=== Amazon Web Services ===
Contributors: bradt, peterolivo
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=5VPMGLLK94XJC
Tags: amazon, amazon web services, CLC
Requires at least: 3.5
Tested up to: 4.1.1
Stable tag: 0.2.2
License: GPLv3

Houses the Amazon Web Services (AWS) PHP libraries and manages access keys. Required by other AWS plugins.

== Description ==

This plugin is required by other plugins, which uses its libraries and its settings to connect to AWS services. Currently, there is only one plugin that requires this plugin:

* [Amazon S3 and CloudFront](http://wordpress.org/plugins/amazon-s3-and-cloudfront/)

This version is modified to work with CLC Object Storage, which is S3 compatible

== Installation ==

1. Use WordPress' built-in installer
2. A new AWS menu will appear in the side menu

== Screenshots ==

1. Settings screen

== Changelog ==

= 0.2.2 - 2015-01-19 =
* Bug Fix: Reverting AWS client config of region and signature
