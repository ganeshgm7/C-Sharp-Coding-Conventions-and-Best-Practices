# C# Coding Conventions and Best Practices

## Naming Convention

- **Pascal Case:** The leading character of each word or phrase is capitalized. (Examples: `ProcessTransaction`, `TaxCalculation`)
- **Camel Case:** Like PascalCase except the first letter is lowercase. (Examples: `totalAmount`, `userName`)
- **Upper Snake Case:** All letters are capitalized, and words are separated with an underscore. (Example: `MAX_SIZE`)

### Specific Naming Guidelines

| Element            | Case               |
|--------------------|--------------------|
| Class name         | PascalCase         |
| Namespace name     | PascalCase         |
| Constructor name   | PascalCase         |
| Method name        | PascalCase         |
| Properties name    | PascalCase         |
| Enum name          | PascalCase         |
| Field name (Public)| PascalCase         |
| Field name (Private)| camelCase         |
| Method arguments   | camelCase          |
| Local variables    | camelCase          |
| Constant name      | UPPER_SNAKE_CASE   |

## General Guidelines

- **Do not use var:** Always use the explicit type. If already used, change to the explicit type whenever working on those blocks.
- **Meaningful Names:** Use clear and descriptive names for classes, methods, properties, and variables.
- **LINQ Queries:** Use meaningful names for LINQ query variables.
- **Formatting and Indentation:** Maintain consistent formatting and indentation. (Use `CTRL + K + D` in Visual Studio)
- **Interfaces:** Prefix interfaces with the letter 'I'.
- **Unused Usings:** Remove unnecessary Namespace usings.
- **Database Calls:** Avoid database calls inside for/foreach loops.
- **KISS & DRY Principles:** Follow the KISS (Keep It Simple Stupid) and DRY (Don't Repeat Yourself) principles.
- **XML Comments:** Use XML comments to document classes, methods, and properties.
