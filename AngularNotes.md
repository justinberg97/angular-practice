## Notes for learning and helping me with Angular. 

## What is Angular? 

Angular is a Single Page Web Application, similar to React 
Every Routing event that happens is done by Angular and is done virtually.

Single Page web apps are much more efficient. 
The server composes the html files and returns it to the user. 
This is done using components.   The HTML document remains the same, but the information rendered is different, because it is receiving info from the backend. 

## Side not I made sure to change my regular css to SCSS

package.json is accessable with npm i even if you are not the primary developer.  ITt has all of our scripts as well. 

## The angular.json file 

the architect section contains the build and serve information.  When we serve our project for dev purposes, 
it means we can modify files and see it live in the browser.  This will help with development. 

the production section has a budget section, which manages the size of the build.  
This is broken into individual "configurations" 

This also has test information. 

## tsconfig.app.json, tsconfig.json, tsconfig.spec.json 

these files are configuring our typsescript files 

## the .editorconfig file 

this file 