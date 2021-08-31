This is a Typescript "Hello world" command-line app, intended for forking. This is a slightly more complicated app demonstrating complex usage of "commander" and the third-party library jsonc-parser.

The sample app takes the name of a JSON property and a path to a JSON file (or `-`) from the command line and deletes all usages of the property within the JSON file, while leaving whitespace and comments unchanged.

The script can be adapted to other JSON-modification tasks by changing the code in `src/app.ts` within the "PERFORM OPERATIONS HERE" comments. Make sure to edit the package name, license and author in package.json when you fork it, and also edit license.txt unless you want to release in the public domain.

Created by Andi McClure.

[Usage instructions](run.txt)

[License](LICENSE.txt)

