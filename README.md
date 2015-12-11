# haxe-default
Haxe default sample. Sample shows how to create js application with loading json data from url and generate html page

gulp file has those functions:

- runs local server.
- watch changes on html and js files (if rebuild application and server runs then gulp runs automatic reload).
 

This sample includes haxe, nodejs and gulp

Install
-------
Install all nodejs packages

        npm install
        
Install msignal (this is Massive library [msignal](https://github.com/massiveinteractive/msignal))

        haxelib install msignal
        

Build app
---------

        haxe build.hxml
        
Run demo
--------

        gulp
        
