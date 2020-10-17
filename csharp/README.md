# coding

C# recommended coding practices

## Naming Conventions

PascalCase for namespaces, clases and methods
camelCase for variables
UPPERCASE for constants

Use nouns for clases and variables.
Use verb for methods.
Use plural only for collections.
Do not use name abbreviations unless defined by the business.
Do not exceed 255 characters in the full name.

Try to use meaningfull naming always

Do not use attribute suffix in Attibutes
Do not use enum suffix in Enums
Do not use numbers and/or simbols in namespaces including class name

private global variables can start with uderscore _

## Code  

Try not to use this. unless is strictly neccessary

```cs
    Example:
    wrong: this.globalVariableName = "some value";
    right: globalVariableName = "some value";
```

Always represent class, method and variable visibility

```cs
    wrong: void SomeVoidMethod(){...}
    right: private void SomeVoidMethod(){...}
```

Order method according its visibility Public goes first, internal second, private third.
Do not use partial clases unless absolutely neccessary.

### Comments

Do not use comments to explain code or business. decisions unless absolutely neccessary.
Use only comments to produce intellicense.
Sing clases with copyright if required by the business

### Identation

Try to use tabs insted of spaces.
Each braces should be in a single line.
Add braces in conditionals, loops and every codig structure which includes braces in its definition.

Prefer interfaces over implemetation (more at OOP).
