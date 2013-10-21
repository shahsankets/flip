# Flip

## A motherfucking split flap display in your motherfucking browser.

### What?

Click this screen grab to view a 56-second demo:

[![Video Screen Grab](http://b.vimeocdn.com/ts/317/513/317513725_640.jpg)](https://vimeo.com/45645328)

Flip is a live streaming Solari Board powered by Sinatra, WebSockets, CSS3 animations and a little bit of hash. It doesn't use any images at all.

### Install it.

~~~ sh
$ git clone
$ cd flip
$ bundle install
~~~

### Run it.

~~~ sh
$ ruby flip.rb
~~~

### Use it.

To view that motherfucker, hit up `http://localhost:3000/`.

To update the message, POST `message=[whatever]` to `http://localhost:3000/` –
for example:

~~~sh
$ curl -d "message=kapow" localhost:3000
~~~

### Current Limitations.

If you want to use it in anything other than WebKit, you'll need to make that work.
