# Write Hello World in TypeScript

## What is TypeScript?

> “TypeScript is JavaScript for application-scale development.”  

TypeScript is an open-source programming language. It is developed by Microsoft. 
It follows JavaScript syntactically but adds more features to it. It is a superset of JS. 

![TS and JS](https://qph.fs.quoracdn.net/main-qimg-1bb226be271cbb969e55513384f2401d.webp)

## Feature of TS

- Purely object-oriented, with features like classes, objects, and interfaces like Java
- TypeScript supports other JS libraries
- Any valid .js file can be renamed to .ts and compiled with other TypeScript files
- TypeScript is portable

## Running a TS code

**Browsers natively does not understand typescript, but they understand javascript. So in order to run typescript codes, first it is transpiled to javascript.**  
**tsc** : is a typescript compiler(transpiler) that converts typescript code into javascript.  
You can install tsc by running following command:

```npm install -g typescript```

## Write your first program

1. Create a file named "helloworld.ts".
2. Add these lines of code.

```
var greet: string = "Greetings"; 
var message: string = "MLH Local Hack Day!"; 
console.log(greet + " from " + message); 
```
3. To compile, run the following command:
```tsc helloworld.ts```

This command will generate a javascript file with name helloworld.js  

4. Run the javascript file using the following command on command line :

```node helloworld.js```

5. Output:

```Greetings from MLH Local Hack Day!```
