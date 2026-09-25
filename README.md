# Name Formatter

**Name Formatter** is a LabVIEW library for converting strings between common programming naming conventions.

## Supported Formats

| Case Type | Input | Output |
|---|---|---|
| Spaced Camel Case | `hello cruel world` | `Hello Cruel World` |
| camelCase | `hello cruel world` | `helloCruelWorld` |
| PascalCase | `hello cruel world` | `HelloCruelWorld` |
| snake_case | `hello cruel world` | `hello_cruel_world` |
| kebab-case | `hello cruel world` | `hello-cruel-world` |

## Usage

The main entry point is:

`Name Formatter Main.vi`

It receives an input string and a case type, and returns the formatted string.

### Example

**Input:**

```text
hello cruel world
