# List of web tools

Here's a list of tools I find useful.

## URL encoder/decoder

[URL encoder/decoder](https://meyerweb.com/eric/tools/dencoder/)

Very useful for decoding garbage redirect/outbound
links from certain websites.

Can be self hosted by copying the source of the site, since
the encoder/decoder function is in javascript, so
it works with a simple docker image
of httpd:alpine locally.

## Online diagram maker

[draw.io](https://www.draw.io/)

I use a self-hosted version of this via docker,
using fjudith/draw.io:alpine image.

Add user: 22312:22312(or whatever)
to ensure the image doesn't run as root.