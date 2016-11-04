# Jsonary linkeddata.center release

This is simplified fork of  [jsonary release repo](https://github.com/jsonary-js/jsonary-release). 
It supports CORS withCredentials for basic http Auuthentication suppot

See [changelog] (CHANGELOG.md) for a list of applied changes.

###  What is Jsonary?

Jsonary is a library for dealing with data and APIs that are described by JSON (Hyper-)Schema.  It can find and fetch schemas referenced from HTTP headers, allowing you to use the API in a flexible way.

It also contains a rendering system, using schema constraints and hyper-schema links to assemble adaptive clients for your APIs.  This is currently only in the browser, but the final steps for getting it working on Node are being worked on.

The goal is that you should be able to write a Jsonary renderer *once*, and it should generate static HTML on Node, and provide part of a snazzy AJAX client on the browser.

