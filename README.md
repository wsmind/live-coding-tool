Live Coding Tool by wsmind
==========================

[Live Version](https://wsmind.github.io/live-coding-tool/)

This is a very basic implementation of a ShaderToy-like tool, but focused more on presenting and teaching than live performing.

It works offline, the shader is stored in the browser local storage, so even in case of a browser crash, usually everything is still around when you restart it.


Shader inputs
-------------

 * time: the time in seconds
 * uv: aspect-corrected 2D space, from -1 to 1 in Y, and from -aspect to +aspect in X

Shortcuts
---------

 * Ctrl+S: save shader (in local storage) and refresh viewport
