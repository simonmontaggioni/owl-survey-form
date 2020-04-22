# Owl Survey Form

An interactive survey form created using react.js, this is a personal project that aim the goal to learn and practice using tecnologies like react.js, sass, and the entire development setup for a professional project

## Getting Started

It is important to note that this project is based on another self project, [react boilerplate](https://github.com/simonmontaggioni/react-boilerplate), for that reasons i recommend you to make it at least a fast read about it.

### Prerequisites

To run this project you need to have node.js installed in your system.

Here a link to [the official node.js page](https://nodejs.org/en/download/package-manager/) installing instructions via package manager ( i use ubuntu like S.O. ) .

### Installing

To get a development env running you need to execute the following command from your terminal:

Installing dependencies:

```bash
npm install
```

Running the devServer:

```bash
npm run start
```

if everthing is OK you should see an output like this:

```bash
    Entrypoint HtmlWebpackPlugin_0 = __child-HtmlWebpackPlugin_0
    [./node_modules/html-webpack-plugin/lib/loader.js!./public/index.html] 1.8 KiB {HtmlWebpackPlugin_0} [built]
Child mini-css-extract-plugin node_modules/css-loader/dist/cjs.js!node_modules/sass-loader/dist/cjs.js!src/pages/CoverPage/CoverPage.scss:
    Entrypoint mini-css-extract-plugin = *
    [./node_modules/css-loader/dist/cjs.js!./node_modules/sass-loader/dist/cjs.js!./src/pages/CoverPage/CoverPage.scss] 3.4 KiB {mini-css-extract-plugin} [built]
    [./node_modules/css-loader/dist/runtime/api.js] 2.46 KiB {mini-css-extract-plugin} [built]
    [./node_modules/css-loader/dist/runtime/getUrl.js] 830 bytes {mini-css-extract-plugin} [built]
    [./src/assets/static/fonts/GreatVibes-Regular.ttf] 79 bytes {mini-css-extract-plugin} [built]
    [./src/assets/static/images/main_screen.svg] 72 bytes {mini-css-extract-plugin} [built]
ℹ ｢wdm｣: Compiled successfully.

```

Go to your favorite browser and open [http://localhost:3000](http://localhost:3000).

Note: This project use a pretty cool tool like husky to make verifications before done a commit.

## Running the tests

To running test you have a variety options.

Runing the tests:

```bash
npm run test
```

Running tests in watcht mode:

```bash
npm run test:watch
```

Running coverage tests:

```bash
npm run test:coverage
```

### Coding style tests

These tests prevent to insert a non standard style code for the project, these test are based on tools like prettier and eslint.

Running the code formatter:

```baxh
npm run prettier
```

Running the code linter:

```baxh
npm run lint
```

and running the linter to make fixes

```baxh
npm run lint:write
```

## Deployment

To generate the necessary files to deploy the system you need to run:

```bash
npm run prebuild
```

This command will generate the bundled file and the chunks used by the deployment server.

## Built With

- [React.js](https://reactjs.org/docs/getting-started.html)
- [Node](https://nodejs.org/en/)

## Contributing

By the moment this is an learning purpose project.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

- **Simón Montaggioni** - _Initial work_ - [Owl survey form](https://github.com/simonmontaggioni/owl-survey-form)
- **Mariana Malavé** - _UI Design_

See also the list of [contributors](https://github.com/simonmontaggioni/owl-survey-form/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Like i mentioned before, this is a learning purpose project, but in the future i would like that it grow to be a beautiful and usable software.
