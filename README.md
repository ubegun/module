# Project struct


myproject/
  |- cmd/
  |   |- myapp/
  |   |   |- main.go
  |
  |- internal/
  |   |- pkg1/
  |   |   |- ...
  |   |
  |   |- pkg2/
  |   |   |- ...
  |
  |- pkg/
  |   |- mypackage/
  |   |   |- ...
  |
  |- api/
  |   |- ...
  |
  |- web/
  |   |- ...
  |
  |- config/
  |   |- ...
  |
  |- scripts/
  |   |- ...
  |
  |- test/
  |   |- ...
  |
  |- docs/
  |   |- ...
  |
  |- README.md



- cmd/: Contains the main application entry points. Each subdirectory within cmd/ represents a separate application or service.
- internal/: Holds internal packages that are specific to your project. These packages are not intended to be imported by external projects.
- pkg/: Contains packages that can be imported by external projects. Each subdirectory within pkg/ represents a separate package or library.
- api/: Includes code related to APIs, such as handlers, middleware, and route definitions.
- web/: Contains code related to web user interfaces, such as templates, static assets, and web-specific handlers.
- config/: Holds configuration files for your project.
- scripts/: Includes scripts or utility tools for your project.
- test/: Contains tests for your project. Organize tests based on the corresponding package structure.
- docs/: Includes project documentation, such as README files, design documents, or usage guidelines.
