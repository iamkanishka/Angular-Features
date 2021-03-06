# Angularfeatures

<p align="center">
<a  target="blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Angular_full_color_logo.svg/2048px-Angular_full_color_logo.svg.png" width="320" alt="Coder Logo" /></a>
</p>

Angular is a development platform, built on TypeScript. As a platform, Angular includes:

A component-based framework for building scalable web applications
A collection of well-integrated libraries that cover a wide variety of features, including routing, forms management, client-server communication, and more
A suite of developer tools to help you develop, build, test, and update your code

Note: AngularJS is the verion 1 of Angular, Angular with Above Version 1 is Just Angular

The Angular Features can be Categorized : - CROSS PLATFORM, SPEED AND PERFORMANCE, PRODUCTIVITY, FULL DEVELOPMENT STORY 

1. Progressive Web Apps
Use modern web platform capabilities to deliver app-like experiences. High performance, offline, and zero-step installation.

2. Native
Build native mobile apps with strategies from Cordova, Ionic, or NativeScript.

3. Desktop
Create desktop-installed apps across Mac, Windows, and Linux using the same Angular methods you've learned for the web plus the ability to access native OS APIs.
 

4. Code Generation
Angular turns your templates into code that's highly optimized for today's JavaScript virtual machines, giving you all the benefits of hand-written code with the productivity of a framework.

5. Universal
Serve the first view of your application on Node.js®, .NET, PHP, and other servers for near-instant rendering in just HTML and CSS. Also paves the way for sites that optimize for SEO.

6. Code Splitting
Angular apps load quickly with the new Component Router, which delivers automatic code-splitting so users only load code required to render the view they request.


7. Templates
Quickly create UI views with simple and powerful template syntax.

8. Angular CLI
Command line tools: start building fast, add components and tests, then instantly deploy.
    1.  `ng g c <component_name>` Command for Creating Component
    2.  `ng g d <directive_name>` Command for Creating Directive
    3.  `ng g s <service_name>` Command for Creating Service


9. IDEs
Get intelligent code completion, instant errors, and other feedback in popular editors and IDEs.


10. Testing
With Karma for unit tests, you can know if you've broken things every time you save.

11. Animation
Create high-performance, complex choreographies and animation timelines with very little code through Angular's intuitive API.

12. Accessibility
Create accessible applications with ARIA-enabled components, developer guides, and built-in a11y test infrastructure.

So We will be Looking These features and Learn as we go on.
1. Create Custom (User) Component by scratch and creating Users Component and imporing user component    
2. How Component Directive Works and  Different ways of integrating HTML code and styles in the Component
3. How we can Import Component as Differnt Variation (As Element, As Attribute, As Class ) in the Correspoding Components
4. Implement Data Binding in the Angular. Understanding String Interpolation in the HTML File
5. Property Binding in the Angular, Binding Property to the attributes in the angular template
6. Event Binding in Angular. Handle Click Events in the Angular
7. Send Data from the Event Binding using $event reserved word
8. Two way Binding in the Form
9. Using ngif with else Condition in HTML Template
10. Styling Dynamically for the Component templates Using ngStyle
11. Apply CSS Classes Dynamically with ngClass Attribute Directive
12. Use of _ngFor Structural Directive for outputting in Lists 
13. Debug Angular Code in Browser using Source maps and also using Augury Extension
14. Send Data from Parent to Child Component using Custom Properties with @Input
15. Send Data from Child to parent Compoenent, Binding to Custom Events using @Output
16. Understand View Encapsulation in Angular
17. Using Local References to Access the HTML Element
18. Access HTML Element in teh DOM & Template with @ViewChild and the type ElementRef
19. Projecting th eHTML Content Written Between the Comnpoenent using ng-Content
20. UnderStanding the Compoenent Life Cycle methods in Angular 
     (ngOnInit, ngOnChanges, ngDoCheck, ngAfterContentInit,ngAfterContentChecked, ngAfterViewInit ngOnDestroy)
21. ngOnInit, ngOnChanges, Constructor of the Angular Componenet life cycle with Example
22. Check  ngDoCheck, ngAfterContentInit,ngAfterContentChecked, ngAfterViewInit ngOnDestroy in Angular
23. Getting Access to the ng-Content HTML using @ContentChild
24. Create Basic Custom Attribute Directive in angular 
25. Using Rendered2 to create the custom attribute directive to manipulate DOM in Angular
26. Accessing the Events for the Directive Element usibg HostListner in Angular
27. Using HostBinding Decorator to Bind the Properties for the Directive element in Angular
28. Sending input Data to the Directive as input properties in the Angular
29. Understand the Concept of the Structural Directives in the Angular
30. Create Custom Structural Directive in teh Angular using Template and ViewContainerRef 
31. How to use ngSwitch, ngSwitchCase, ngSwitchDefault Directive in Angular
32. Services Introdcution, Create a simple service and use service in Components in Angular
33. Injecting Services into Components using Dependency Injection through Providers in the Angular
34. Create  new Service and use the Service Data in Angular, plass Data from the serive to componenets
35. Understand the Hierarchical Injection of the Services of Instances in the angular
36. Injecting Services into another Services, Using of @injectable decorator in tge angular    
37. Making the cross componenet communication suing the EventEmitter in Service
38. For Angular-Routing Features, you can Follow this Repository - https://github.com/iamkanishka/Angular-Routing-Featuers




# Follow the Below Steps

Note:- Before Starting with this Project, Please make sure you have installed latest stabled version of [Nodejs](https://nodejs.org/en/) Application in your System 

For Installation of Angular CLI and Running the Angular Application Please run the below Commands in you System 
## Installing Angular CLI


Install the CLI using the npm package manager:  `npm install -g @angular/cli`

## Create Angular Project
To create, build, and serve a new, basic Angular project on a development server, go to the parent directory of your new workspace use the following commands: `ng new my-first-project`

## Development server

To Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
