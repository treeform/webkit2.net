# webkit2.net

My take on embedded webkit for .net (based on open-webkit-sharp, which is based on webkit.net) in 2014.

## Why?

I think the universe is moving to the web and web based apps. I want to write a single web based app and have it run everywhere. But I want the desktop-web-based app to be able to access some OS features.

When I tried [Open-Webkit-Sharp](https://code.google.com/p/open-webkit-sharp/) (last updated in 2012) did not compile out of the box and had odd binary and release folders everywhere. But still used the “binary” folder. I made it put all the binaries in the binary folder. (Some one already ranted about this [here]( http://marcclifton.wordpress.com/2013/02/05/a-build-of-open-webkit-sharp-that-actually-compiles-and-runs/).

While [Webkit.net](https://github.com/webkitdotnet/webkitdotnet) the original project did not have many of the “private” methods of webkit exposed to be used. So it was not as powerful as open-webkit-sharp. It had problems shopping the developer tools which I need to develop Desktop-web hybrids.


I hope you may find this helps you some how.
