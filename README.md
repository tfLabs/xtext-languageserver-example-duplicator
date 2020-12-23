# Xtext Visual Studio Code Example Duplicator

This duplicate [Xtext Visual Studio Code Example](https://github.com/cdietrich/xtext-languageserver-example) and convert language extension.

## How to duplicate

Requires Visual Studio Code (VS Code) with version 1.4.0 or greater to be on the path as `code` and Java 8+ available as `java`.

- `./gradlew duplicateXtextVscode`
- `cd xtext-languageserver-example-duplicated`
- `./gradlew startCode`

This will start VS Code and after a few seconds load the `demo` folder of this repository.
