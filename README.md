# angular2
This is an example using Visual Studio 2015 and Angular 2 alpha 39.

The code is the same as https://angular.io/docs/js/latest/quickstart.html

If you want to try to do it from scratch do not forget to add the following values in the csproj file:
(unload project and edit the file)
  
  < TypeScriptEmitDecoratorMetadata >True < / TypeScriptEmitDecoratorMetadata >
  
  < TypeScriptExperimentalDecorators >True < / TypeScriptExperimentalDecorators >
  
  The use of SystemJs is with the js file. I could use the same way the example shows.
  The example says:
  <script>System.import('main');</script>
  The way that I use was
  <script>System.import('main.js');</script>
  
  I am going to do more example later.
