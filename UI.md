## 😼😼 Fit Questions 😼😼
# HTML
- What's HTML 5
- What's semantic elements in HTML
- What's a web worker (How it's useful)
- what's `srcset` attribute and how does it work (sizes, src)
- async attribute in HTML <script> 


# CSS / SASS / LESS :art: :art:

- What type of selectors you know?
- how the sibling combinator works? `p ~ span { color: red;}`
- how the child combinator works `div > span { color: blue; }`
- how can I add a border black to a button when it's : 
    1 - Active
    2 - Focused
    3 - Hovered

- pseudo-elements: explain `:before` and `:after`
- pseudo-elements: explain `:first-element` vs `:first-line`
- pseudo classes: :`:first` vs `:first-chiild` `:first-of-type`
- pseudo classes: Explain both `:host` and `:host()`
- box sizing: `border-box` vs `content-box` , explain the difference
- What the `object-fit` property does and how and why use it. (fill, contain, cover, scale-down. none).
- `display:none` vs `visibility: hidden;`
- Whats margin collapsing
- flex box: explain
- flex box vs float (What do you prefer and why)
- Having this (Explain), I want the child divs to be rows separated from left to right with an evently space.
    ```<div class="box">
          <div>One</div>
          <div>Two</div>
          <div>Three
              <br>has
              <br>extra
              <br>text
          </div>
        </div>
    ```
- If I need to display two different layouts of my web page depending on the screen size, which approach should I take to do it.
- transitions vs animations
- whats a keyframe
- What's a css preprocessor
- What's a mixin
- mixin vs functions
- why would I need a variable on a scss file?
- What's specificity


# Acessibiility

- Why should I use a button tag instead of a DIV with a click action?.
- Why should I use a button with a link style instead of an empty href or href="#".
- What's an screen reader?
- What's ARIA

# Javascript
- What's Javascript
- What's ECMA Script, and how is that related to JavaScript
- What's a clousure and how/when to use it
    Example:
    ```
        function makeFunc() {
          var name = 'Mozilla';

          function displayName() {
            console.log(name);
          }

          return displayName;
        }

        makeFunc();
        // Mozilla
    ```
- What's a curried function, how to use it.
    Example:
    ```
        function makeAdder(x) {
          return function(y) {
            return x + y;
          };
        }
    ```
- What's new in ES6. Ex:(Arrow fun, spread operators, async, classes etc)
- What's recursion
- Functional programming.
- What's a pure function
- How to use the reduce operator, and why.
- Async/await
- Callback vs Promises vs Async.
- == VS ===
- Name ways to get elements from DOM
- What is spread operator, Provide examples: `const a = [...b];`
- What's detructuring, Provide examples.
    Example:
    ```
        const c = {a: 'hello', b: 'World' };
        myMethod(c);
        
        myMethod({a, b}) {
           console.log(a + ' ' + b);
        }
    ```
 - Arrow Functions benefits
 - What's Context
 - What's Scope
 - How to check an array, and array legth
 - Name array methods and usage (Push, Pop, Shift, unshift)
 - What NEW word means, and what is the usage
 - What's a IFFE (Immediately Invoked Function Expressions) (Apples for AngularJS) 
 - var vs const vs let
 - What's Hoisting
 - What's Event Loop, Explain (Call Stack => Event Table => Event Queue => Event Loop)
 - What's Bubbling (how to prevent, when to prevent)
 - `event.target` vs `event.currentTargent`
 - `event.stopPropagation()` vs `event.stopImmediatePropagation()`
 - What's Capturing (Similar to bubbling)

# Angular JS 🚀🚀

- What's a Module
- What's a Factory
- What's a Service
- Factory VS Services (Name Differences)
- What's structural Directives (How to build one)
- What's a component
- What's a Filter (Name those you know) (How to build one)
- Components vs Directives
- ng-cloack
- translate-cloack
- link vs postlink
- is it correct to call the DOM from the controller?
- $q.all
- ngRoute VS UI Route
- what's a resolve in a route
- What's $scope.
- What's $rootscope
- explain $scope.emmit and $scope.broadcast (Also $scope.on)
- What's a Promise
- Promise vs callback vs await async (If angular >2 vs Observable )

# Angular 🚀🚀

- What should I do if I  want to execute a function when the size of the screen is reduce to 320px.
- I have a parent component and 1 child component, what can I do to share info with my child component. And What can I do to
share info from the child to the parent component.
- I have a parent component with two child components, what can I do to share info between the two child components.
- What's view encapsulation, what types do you know?.
- What is a service, how to use it.
- What are life cicle hooks, name which of them you know.
- What's is the difference between Observable and Promises.
- How can I lazy load a module.
- I want to add an authorization header on every Http(ajax) Call on my application, how can I do it.
- I want to pre-load some data before I load a route, what should I do. 
- I want to validate if a user is logged in on my app before a page is loaded, what can I do.
- Contructor vs OnInit
- Do you use typescript, and why do you think this is good.
- Angular Animations module, what it is, why is good, why is this better than using CSS Animations.

# Angular Architecture :ship:

- Why would you included a Core Module to your app.
- Why would you included a Shared Module to your app.
- What is an SPA
- What's AOT (Ahead of time compilation) vs JIT
- Which are the building blocks of angular.
- What's dependency injection.
- ivy

# Angular Unit tests :zap:
- TestBed
- Tick
- Detect Changes
- Why it's good to do unit testing
- Coverage (Branches, Statements)
- Why do we need to mock data
- Spy

# RxJS ☢️☢️

- What's a pipable operator
- What's subscribe, what is used for?.
- what's Debounce time
- Switch map
- Fork Join
- When would you use a Subject
