# MRP - A Brief Introduction to JavaScript
## Creating CRUD (Create, Read, Update, Delete) applications in Vanilla JavaScript

#### Method One:
#### - DOM-focused Vanilla JavaScript approach, utilising the DOM to perform CRUD operations and update local storage appropriately for re-rendering updated elements within the DOM.

#### Method Two:
#### - Data-driven Vanilla JavaScript, using one render function and updating local storage, assigning data attributes and targeting them for string-interpolation.

#### Note: Do notice that the second, data-driven method is more close to what we have with front-end frameworks such as React, Vue and Angular. The reason for this is this method *is* a better approach in some circumstances and has pitfalls in other areas. For example, with the DOM-focused app we simply add extra elements to the DOM, this way it ensures that only the element we wish to update or that *has changed* will be updated. With the data-driven approach we see that *any time* something changes, or an attribute is updated, the *entire* app will re-render; this is not ideal either. This, in part, is one of the very distinct reasons we have front-end and UI development frameworks and libraries that help us perform these actions in a more concise and intuitive way.

##### It should be known before inspecting the code to each simple CRUD application that each of these methods of writing JavaScript code to perform actions, update DOM elements or build a sustainable, scalable and maleable User Interfaces are neither deemed to be the best ways in which to do so *or* supposing that these JavaScript skills should be taken for gospel in front-end development, it is simply a way in which to visualise further the operations of JavaScript that let us interact with the browser in a more primitive, granular sense. 

##### These examples simply demonstrate two alternate ways in which the same simple, CRUD application can be written with a short HTML block and some corresponding JavaScript functions in an attempt to unlock deeper levels of knowledge about the inner-workings and what's going on "under the hood" before jumping into a front-end framework like React or Vue.

## Getting Started w/ "MRP - A Brief Introduction to JavaScript"
#### You don't need anything other than a text-editor (IDE, pref. VSCode) to view code, a browser (pref. Google Chrome), and that's it!
##### 1. Drag and drop the CRUD .html files into Google Chrome.
##### 1(alt.) Open VSCode, select 'Extensions', install 'Live Server' by Ritwick Dey. Navigate to bottom right of VSCode window, select 'Go Live' button (this will open a local html-server window on Chrome).
##### 2. Right-click on the web browser window were the app is loaded, click 'Inspect' ('Inspect Element' on Windows).
##### 3. Open the 'Console' to see what actions are taking place in the app when you add new items, edit them or delete them.
##### 4. Navigate to 'Application' in Inspect side-panel, select 'Local Storage'. From here you can see what data is being saved into local storage (strings).
##### 5. Click on the 'Value' header to view the data format.

#### The .htmls files in each folder contain the exact same 'application', each portion of code generates the exact same output. One difference is that they are designed differently, not the look and feel - but the code structure and the approach to which the actions we need to perform are performed.

##### * Note: There is an annotated version of the DOM-focused CRUD App, this attempts to explain each action and start to dismantle the code in a way that can be interpreted at a lower-level than the plain file w/out comments. The data-driven approach will be annotated soon. 
###### * Until then, can you see the differences in each approach? Do you see the drawbacks *both* methods have? If you are familiar with JavaScript already, what might you have done differently? Have you had experience writing ES6 standard and contemporay JavaScript before? Have you used or researched a front-end framework like React or Vue? Why do we use them?

## - Research materials and relevant documentation:
##### JavaScript - https://developer.mozilla.org/en-US/docs/Web/JavaScript
##### JavaScript - Objects and Arrays - https://eloquentjavascript.net/04_data.html
##### Why aren't these functions? What are these arrows? All that, and more, here - https://medium.com/recraftrelic/es5-vs-es6-with-example-code-9901fa0136fc
##### React.js - https://reactjs.org/
##### DOM (Document Object Model) - https://en.wikipedia.org/wiki/Document_Object_Model
##### Local Storage - https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
##### Query Selectors - https://beamtic.com/getelementbyid-vs-queryselector
##### Variables: let & var - https://stackoverflow.com/questions/762011/whats-the-difference-between-using-let-and-var
##### Event Listeners - https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener
##### Why use preventDefault()? - https://developer.mozilla.org/en-US/docs/Web/API/Event/preventDefault
##### Blank Strings or Null Values? - https://tinyurl.com/y548dltw
##### Template Literals - https://tinyurl.com/y2zj5baf
##### String Interpolation, what is it? - https://dmitripavlutin.com/string-interpolation-in-javascript/
##### Array.prototype.map() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
##### Array.prototype.forEach() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach
##### Array.prototype.push() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
##### Array.prototype.join() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join
##### When to use .map() or .forEach()? - https://codeburst.io/javascript-map-vs-foreach-f38111822c0f
##### Window.prompt - https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt
##### Node.parentElement - https://developer.mozilla.org/en-US/docs/Web/API/Node/parentElement
##### DOM remove() Method - https://www.w3schools.com/jsref/met_select_remove.asp
##### Element.getAttribute() - https://developer.mozilla.org/en-US/docs/Web/API/Element/getAttribute
##### JSON Parse() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse
##### What's Best? .innerHTML, .innerText or .textContent? - https://medium.com/better-programming/whats-best-innertext-vs-innerhtml-vs-textcontent-903ebc43a3fc

### by Matt Stevenson | Front-End Developer @ MRP
