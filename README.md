# vscode-angular2-test-snippets

Following John Papa's example on his handful [vscode-angular2-snippets](https://github.com/johnpapa/vscode-angular2-snippets),
here is my **vscode-angular2-test-snippets** which is a collection of code snippets bringing recipes for each type of common
in Angular 2 framework.

## Installation

Search for "angular2 test" in Visual Studio Code, or just jump straight to 
https://marketplace.visualstudio.com/items?itemName=MarinhoBrandao.Angular2Tests

You can alternatively fork/clone/download this repository and copy and paste the content of
`typescript.json` into your file for customized snippets, following 
https://code.visualstudio.com/docs/customization/userdefinedsnippets.

## Snippets

### ng2-test-component

Basic component test recipe, including basic operations on DOM `nativeElement`, component
creation and compilation and basic assertion examples.

### ng2-test-component-routed

This is a more complex component, including route manipulation, spying methods and manipulation
of change detection.

### ng2-test-component-properties

Test recipe covering a component with Input, Output and HostBinding.

### ng2-test-component-service

Test recipe covering a component with async and sync services.

### ng2-test-directive

Test recipe to cover a **Directive**, with a mocked container component implementing such 
directive as an example of it. Includes basic coverage on the DOM `nativeElement`.

### ng2-test-form

Recipe for isolated unit test covering a Reactive Form.

### ng2-test-guard

Recipe for isolated unit test covering a Route Guard.

### ng2-test-pipe

Test recipe covering a **Pipe**, which is mostly a single pure function in a class. Works
mostly as simple unit test, but with Pipe basic structure.

### ng2-test-observable

Basic test recipe covering observable and respective subscriptions.

### ng2-test-redux

Test recipe covering an action and consequent state change consuming by how it is implemented in
**[ng2-redux](https://github.com/angular-redux/ng2-redux/)** and
**[Redux](http://redux.js.org/)**.

### ng2-test-without-testbed

The most basic type of test, which totally unit driven, ideal to write isolated tests of
specific pure functions, classes and reducers.

### ng2-test-service

A simple test recipe using `beforeEachProviders` to setup a service test.

### ng2-test-mockbackend

A test recipe using **MockBackend** and **MockConnection** to mock HTTP requests.

### To be done

- ng2-test-routes
- ng2-test-e2e-jasmine
- ng2-test-e2e-cocumber

## How this repository is maintained?

It follows as close as possible the standards recommended in
https://angular.io/docs/ts/latest/guide/testing.html

## How to contribute?

If you see these snippets are outdated according to the URL above, file your Pull Request with updates or just
let me know through the (issues section)[./issues/].

Have fun! 
