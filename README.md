# laravel-snippets

## installation

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install m7md3omer.laravel-relationship-snippets`

### OR

go to the [extension page][1] to install

## Features

This snippet extension allows you to quickly scaffold relationship, test functions and classes and general functions code in your laravel application models.

---

|  abbreviation  |         code snippet generated          |
| :------------: | :-------------------------------------: |
|    phpFunc     |     Generates a public php function     |
|   phpPrivate   |    Generates a private php function     |
|      test      |         Generates test function         |
|  testFeature   |      Generates feature test class       |
|    testUnit    |        Generates unit test class        |
|     hasOne     |     Generates a hasOne relationship     |
|   belongsTo    |   Generates a belongsTo relationship    |
|    hasMany     |    Generates a hasMany relationship     |
| belongsToMany  | Generates a belongsToMany relationship  |
| hasManyThrough | Generates a hasManyThrough relationship |
| hasOneThrough  | Generates a hasOneThrough relationship  |

---

![tests](https://github.com/m7md3omer/laravel-snippets/blob/master/screenshots/test.gif?raw=true "test snippets")

---

![function](https://github.com/m7md3omer/laravel-snippets/blob/master/screenshots/screen2.png?raw=true "function snippet")

---

![relationship-snippet](https://github.com/m7md3omer/laravel-snippets/blob/master/screenshots/screen2.png?raw=true "relationship snippets")

## Requirements

This extension works only with php files.

## Contribution

Feel free to add more snippets related to laravel relationships.

make sure that you checkout to a new feature branch before you start adding your snippets.

## Release Notes

### 1.0.0

- Initial release of laravel relationship snippets

### 1.0.1

- Added more snippets and fixed some bugs

### 1.1.0

- Added test functions and classes snippets

### 1.1.2

- applied standard code formatting for php
- added gif and images to extension details

[1]: https://marketplace.visualstudio.com/items?itemName=m7md3omer.laravel-relationship-snippets&ssr=false#overview
