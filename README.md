# @sakes/randomid-generator
* [General info](#general-info)
* [Setup](#setup)

## General Info
This package provides a simple function for generating random IDs. The generated IDs can contain uppercase and lowercase letters and numbers, and the length of the ID can be specified as an argument when calling the randomID function.

## Setup
To use this package, you can install it using npm or yarn:

```
$ npm install @sakes/randomid-generator
$ yarn add @sakes/randomid-generator
```

You can then import the randomID function and use it to generate random IDs:

```
$ const randomID = require('@sakes/randomid-generator');
$ 
$ console.log(randomID(10));
$ // Output: "aBcDeFgHiJ"
```