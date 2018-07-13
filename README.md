# Custom schematics with nx workspace demo application

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) using [Nrwl Nx](https://nrwl.io/nx).

This is a demo workspace with a custom angular cli component schematics.

Read the [blog post](https://www.lambda-it.ch/blog/post/custom-schematics-with-nx-workspace) to reproduce this example.

## Instructions

1. Clone this repository
2. Run `npm install`
3. To create a new custom component, run `ng g demo-collection:custom-component TestPage --app=demo-app`
4. The component should be generated, you can now use it in a template `<schematicsdemo-test-page></schematicsdemo-test-page>`
5. Run `npm start` to start the application.
