## React+Typescript Setup with Webpack

→ This is a React setup created with TypeScript and Webpack, which provides an efficient development environment for building modern web applications.

With the help of Webpack, this setup allows you to easily bundle and optimize your code, while TypeScript adds static type checking to your JavaScript code, making it more reliable and easier to maintain.

### To start development server, if you are using yarn

```bash
$ yarn start
```

or if you are using npm

```bash
$ npm start
```

### To make production build, if you are using yarn

```bash
$ yarn build
```

or if you are using npm

```bash
$ npm run build
```

### dist folder

→ when you will run `$ yarn build` command in your terminal you will get `dist` folder in your directory

→ "dist" folder typically stands for "distribution" and contains the bundled and optimized code that is ready to be deployed to production.

→ During the Webpack build process, the source code is transformed and optimized into a single or multiple bundles, which are typically stored in the "dist" folder. The bundled code includes all the necessary dependencies and assets required for the application to run in a production environment.

→ The "dist" folder may also contain other files, such as HTML, CSS, and images, that are required to serve the application. These files are typically optimized for performance and compressed to reduce the application's load time.

→ Once the "dist" folder is generated, the contents of the folder can be deployed to a server or hosting platform to make the application available to end-users.
