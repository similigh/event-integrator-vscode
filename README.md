# Event-Integrator VS Code Extension

Official VS Code extension for Event-Integrator configuration, debugging, and development.

## Features

- **Syntax Highlighting**: Full syntax support for .event-integrator.yaml and .event-integrator.json files
- **IntelliSense**: Autocomplete and schema validation for configuration files
- **Debugging**: Integrated debugger for Event-Integrator with breakpoints and step execution
- **Configuration Editor**: Visual editor for Event-Integrator settings with schema guidance
- **Code Snippets**: Pre-built snippets for common Event-Integrator patterns
- **Live Preview**: Real-time validation and error detection

## Installation

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Search for "Event-Integrator"
4. Click Install

Or install from command line:
```bash
code --install-extension similigh.event-integrator
```

## Quick Start

1. Create an `.event-integrator.yaml` file in your workspace
2. Start typing - IntelliSense will provide suggestions
3. Errors and warnings appear inline with helpful messages
4. Use snippet shortcuts for common patterns

## Configuration

Configure extension settings in VS Code preferences:
- `eventIntegrator.configPath`: Default path to configuration files
- `eventIntegrator.validateOnType`: Enable real-time validation
- `eventIntegrator.theme`: Color theme for editor

## Debugging

1. Set breakpoints in event handlers
2. Press F5 to start debugging
3. Step through event processing
4. Inspect payloads and variables

## Commands

- `Event-Integrator: Open Settings` - Open configuration editor
- `Event-Integrator: Validate Config` - Validate current file
- `Event-Integrator: Format Document` - Format YAML/JSON

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for development guidelines.

## License

MIT License - see LICENSE file for details
