# Copilot Instructions for Flutter/Dart Project

## Project Structure
- `lib/`: Main source code
  - `src/`: Core application code
  - `widgets/`: Reusable widgets
  - `screens/`: App screens/pages
  - `models/`: Data models
  - `services/`: API/backend services
  - `utils/`: Helper functions
  - `constants/`: App-wide constants

## Coding Standards
- Use camelCase for variables and functions
- Use PascalCase for classes and widgets
- Prefix private members with underscore
- Use `const` constructors when possible
- Follow Flutter's style guide

## Flutter Conventions
- Prefer composition over inheritance
- Use named parameters for widgets
- Implement `const` constructors
- Separate business logic from UI
- Use extension methods for code organization

## State Management
- Use Provider/Riverpod for state management
- Keep state at lowest required level
- Use ValueNotifier for simple state
- Implement repository pattern for data access

## Testing
- Write widget tests for UI components
- Unit test business logic
- Integration tests for critical flows
- Use `flutter_test` framework
- Maintain 80%+ test coverage

## Code Generation
- Use `freezed` for data classes
- Generate route using `go_router`
- Use `json_serializable` for JSON parsing

## Performance
- Avoid unnecessary rebuilds
- Use const widgets when possible
- Implement pagination for lists
- Cache network resources
- Profile regularly with DevTools