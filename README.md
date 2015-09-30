# bowser-body-class

A simple edit to bowser.js to put the browser type and version in the body tag's class.

Original here: https://github.com/ded/bowser

You can initialize the class thing by the following code:

<pre>bowser.SetBrowserClass();</pre>

It appends two classes to the body - Chrome Chrome45

Where the first one is the general browser and the second is the browser version is appended to the name.

In the case of mobile it will append _mobile to the general browser, like so - Chrome_mobile Chrome44
