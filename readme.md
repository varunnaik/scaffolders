While tools such as `create-react-app` and `express-generator` exist to scaffold out their respective projects, they don't generally do a complete setup with all embellishments and packages typically used in a project.

This sets up a more ready-to-go environment by building on top of these tools.

The main advantage of using this over a boilerplate repository is that this approach closely tracks the current recommended setup of the official scaffolders and is less likely to be out of date and is easier to maintain.

### React scaffolder              

This uses create-react-app to build an application, and then sets up some essential libraries, Jest for testing, and prettier.
Does not add Redux.

Call it with
`./setup-react [--typescript] path-to-app
