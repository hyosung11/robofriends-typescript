# robofriends-ts
Udemy tutorial - adding TypeScript to a react app

To run the project:

1. Clone this repo
2. Run `npm install`
3. Run `npm start`
4. Start adding types!


```JavaScript
hyosung11@HyoSungs-iMac robofriends-typescript % npm start

> typetype@0.1.0 start /Users/hyosung11/projects/robofriends-typescript
> react-scripts-ts start


There might be a problem with the project dependency tree.
It is likely not a bug in Create React App, but something you need to fix locally.

The react-scripts-ts package provided by Create React App requires a dependency:

  "eslint": "5.6.0"

Don't try to install it manually: your package manager does it automatically.
However, a different version of eslint was detected higher up in the tree:

  /Users/hyosung11/projects/robofriends-typescript/node_modules/eslint (version: 6.8.0)

Manually installing incompatible versions is known to cause hard-to-debug issues.
To fix the dependency tree, try following the steps below in the exact order:

  1. Delete package-lock.json (not package.json!) and/or yarn.lock in your project folder.

  2. Delete node_modules in your project folder.

  3. Remove "eslint" from dependencies and/or devDependencies in the package.json file in your project folder.

  4. Run npm install or yarn, depending on the package manager you use.

In most cases, this should be enough to fix the problem.
If this has not helped, there are a few other things you can try:

  5. If you used npm, install yarn (http://yarnpkg.com/) and repeat the above steps with it instead.
     This may help because npm has known issues with package hoisting which may get resolved in future versions.

  6. Check if /Users/hyosung11/projects/robofriends-typescript/node_modules/eslint is outside your project directory.
     For example, you might have accidentally installed something in your home folder.

  7. Try running npm ls eslint in your project folder.
     This will tell you which other package (apart from the expected react-scripts-ts) installed eslint.

If nothing else helps, add SKIP_PREFLIGHT_CHECK=true to an .env file in your project.
That would permanently disable this preflight check in case you want to proceed anyway.

P.S. We know this message is long but please read the steps above :-) We hope you find them helpful!

npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! typetype@0.1.0 start: `react-scripts-ts start`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the typetype@0.1.0 start script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/hyosung11/.npm/_logs/2019-12-31T01_49_48_251Z-debug.log
hyosung11@HyoSungs-iMac robofriends-typescript %
