# Node.js examples from Pillora's book

<table style="font-family:Helvetica,Arial;font-size:14px;line-height:1.6;">
  <tr>
  <td style="border:0;padding:0 10px 0 0;min-width:120px;"><a href="http://nodejs.org/"><img src="https://nodejs.org/static/images/logos/nodejs-new-pantone-black.png" width="120"/></a></td>
  <td style="border:0;padding:0;vertical-align:text-top;">The <strong><code>samples_Pillora\</code></strong> directory contains <a href="http://nodejs.org/" alt="Node.js">Node.js</a> examples presented in <a href="https://www.packtpub.com/web-development/getting-started-grunt-javascript-task-runner">Pillora's book</a> "<i>Getting Started with Grunt: The JavaScript Task Runner</i>" (Packet, 2014).<br/>
  Github: <a href="https://github.com/jpillora/gswg-examples.git">https://github.com/jpillora/gswg-examples.git</a></td>
  </tr>
</table>

### `4-02-project`

Executing the **`npm start`** command in directory **`samples_Pillora\4-02-project\`** performs two tasks:

- it builds your project using [Grunt](https://gruntjs.com/) (see Grunt tasks in file **`Gruntfile.js`**).
- it opens the **`build/app.html`** Web page in your default web browser.

<pre style="font-size:80%;">
> npm i & npm start
up to date in 0.748s

> gswg-4-02-project@0.1.0 start C:\nodejs-examples\samples_Pillora\4-02-project
> grunt & node ./npm_scripts/start_browser.js build/app.html

Running "coffee:build" (coffee) task
>> 1 files created.

Running "stylus:build" (stylus) task
>> 1 file created.

Running "pug:build" (pug) task
>> 1 file created.

Done.
</pre>

### `4-03-project`

Same as `4-02-project`.

*[mics](http://lampwww.epfl.ch/~michelou/)/April 2018*