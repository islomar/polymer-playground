# Polymer playground
Playground for learning about Polymer


##General Notes
* Created by Google
* Implementation for Web Components
* **Goal:** to be able to reuse "things" in the web in a native/standard way.
Polymer is an implementation for the standard Web Components.
* Polymer App Toolbox: https://www.polymer-project.org/1.0/toolbox/
  * To create an app
* **Web Components**
  * It's a collection of technologies for reusing HTML components.
  * Templates
  * HTML Imports: 
    * `<link rel=”import” href=”include.html”>`
  * Shadow DOM:
    * Technology responsible for scoping our element and not letting JS/CSS overflow out of it, so it is enclosed, separate, reusable block.
  * Custom elements:
    * Technology responsible for creating our own elements, just like the native ones, like <input>
  * Links:
    * Introduction to Web Components: https://www.w3.org/TR/components-intro/
    * https://www.w3.org/wiki/WebComponents/
    * https://github.com/w3c/webcomponents



##Getting started with Polymer.js
Pluralsight course by Bill Stavroulakis (from Microsoft).
Plunker code: http://bstavroulakis.com/pluralsight/courses/polymer-js-getting-started/


###Course overview
Current WC limitations:
* Web Components can not be used in every browser yet: `http://caniuse.com/#search=web%20components`
* If we used WC today, it would only work in Chrome and Opera.
* Shadow DOM is in Editor's Draft, which means that it will change: https://w3c.github.io/webcomponents/spec/shadow/

Polymer offers:
* Being able to use WC today.
* A graceful fallback for WC: in Chrome it will use the standard native WC, but in IE it would run Polymer in order to mimic the WC behaviour.
* Same declaration as specs change
* Helper functions and features
* Just be getting better/faster
* Polymer community: take advantage of everything created by other people

Polymer vs other frameworks:
* Angular 2 example: https://plnkr.co/edit/zYDDOfqSPTbfw4nPnzlU?p=preview
* React.js example:  https://plnkr.co/edit/Wxl9Jc7kE26TbMAtAIbk?p=preview
* Ember.js example:  https://plnkr.co/edit/neq4TLRe5QouzPtTUYsE?p=preview
Polymer is built on native functionality, and not on customed solutiones.

###Your first element
* "Including Polymer" example: 
  * https://plnkr.co/edit/OT6VcKZPJwlrM1G1WVNq?p=preview
  * It appears all the 3 files
  * You include first the JS, for having the fallback in case the import is not supported by the browser.
* http://bit.ly/downloadpolymerjs
  * polymer:
    * https://www.polymer-project.org/1.0/docs/devguide/experimental
    * polymer.html
    * polymer-mini.html
    * polymer-micro.html
  * webcomponentsjs: created by the Polymer team as fallback for WC native functionality.
    * MutationObserver: Polymer uses it to react to changes to a DOM.
    * webcomponents.js contains CustomElements, HTMLImports, MutationObserver and ShadowDOM
    * webcomponents-lite.js is like webcomponents.js, but without ShadowDOM
* When importing an HTML, you import EVERYTHING: HTML, JS, CSS...
* Polygit CDN: https://polygit.org/	>> not recommended for Productions environment, it is not an optimized method for loading resources.


###Events and behaviours




##Introducción a Polymer
https://www.adictosaltrabajo.com/tutoriales/polymer-2/
Una de las herramientas que nos permiten gestionar el ciclo de desarrollo de una aplicacion HTML5 es **Yeoman**, que se compone de otras tres herramientas: **Bower** para la gestión de paquetes, **Grunt** para generar, previsualizar y testear nuestros proyectos y **Yo** para gestionar ambos.

bower.json para dependencias que se tratan con Bower y Gruntfile.js para el despliegue y otras tareas

Install:
* `sudo npm install -g yo`
* `npm search yeoman-generator`
* `sudo npm install generator-polymer -g`
* Run `yo polymer`
* I had to install *grunt* manually: `npm install grunt`
* `sudo grunt serve`



##Angular2 + Polymer
https://www.adictosaltrabajo.com/tutoriales/integracion-de-angular-2-con-polymer/



##Paradigma Digital - [Meetup] Polymer: construyendo componentes web
https://www.youtube.com/watch?v=wG1j-sZVNBQ



##Official tutorial
https://www.polymer-project.org/1.0/start/
You need to install:
* Node
* Bower (with npm)
* polymer-cli (with npm)
Tutorial: polymer-first-elements.zip
