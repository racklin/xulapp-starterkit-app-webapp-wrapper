Webapp Wrapper For XULApp StarterKit
-----------------------------
Webapp Wrapper is a simple build script for XULApp StarterKit.

It packaging HTML5 Web Application as XULApp StarterKit's add-on.


Benefits
-----------------------------

* Latest HTML5 support (Same as Firefox 18, and easy to use new Gecko versions as they are released)
* Can using XULApp StarterKit Auto-load Modules .


Download pre-build XPI
-----------------------------
Download pre-build XPI in [downloads](https://github.com/racklin/xulapp-starterkit-app-webapp-wrapper/tree/master/downloads)


Get started
-----------------------------
Build Webapp Wrapper for your web application:

1. Fork this project.
2. Copy your web application to webapp/ directory.
3. Change install.rdf and build.sh for your project name.
4. run build.sh


Auto-Load Modules in HTML5
-----------------------------
Added init.js to your html file. EX.

```
<script src="chrome://xulapp/content/init.js"></script>
```

And now in javascript you can using *XULApp* global variable to access Modules.

```
<p><a onclick="XULApp.Notification.info('Hello', 'World'); return false;">Demo XULApp XPCOM Notification</a></p>
```


License
-----------------------------
Webapp Wrapper For XULApp StarterKit are licensed under the [MPL License].
See LICENSE for more details.
