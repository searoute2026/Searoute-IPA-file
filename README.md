# Native iOS Web App Framework

This repository contains the native iOS source code for building full-featured applications from existing mobile-optimized web platforms.

The framework provides integration between web content and native iOS capabilities, allowing developers to package web applications as native iOS apps while maintaining access to device features and platform-specific functionality.

## Features

* Native iOS application container
* Web-to-native bridge support
* Push notification integration
* Camera and file access
* Location services support
* Deep linking
* Custom native modules
* Swift Package Manager dependency management

---

## Getting Started

This project uses Tuist for project generation and dependency management.

### Prerequisites

Install Tuist:

```bash
curl -Ls https://install.tuist.io | bash
```

### Generate the Xcode Project

```bash
tuist generate
```

This command will:

* Generate the Xcode workspace and project files
* Resolve Swift Package Manager dependencies
* Configure build settings and targets

### Open the Project

```bash
open App.xcworkspace
```

### Build the Application

Using Tuist:

```bash
tuist build App
```

Or build directly through Xcode.

---

## Project Structure

```text
.
├── App
├── Core
├── Features
├── Resources
├── Tuist
├── Project.swift
└── README.md
```

---

## Development Commands

Generate project:

```bash
tuist generate
```

Clean generated files:

```bash
tuist clean
```

Edit manifests:

```bash
tuist edit
```

Visualize dependencies:

```bash
tuist graph
```

Build application:

```bash
tuist build
```

---

## Configuration

Application settings can be customized through the project configuration files and environment settings.

Common customizations include:

* App Name
* Bundle Identifier
* App Icons
* Splash Screens
* Web Endpoint URL
* Push Notification Configuration
* Native Permissions

---

## Requirements

* macOS
* Xcode 16+
* Swift 5.10+
* Tuist
* iOS 16.0+

---

## License

Copyright © 2026.

All rights reserved.

This software is proprietary and intended for private use. Redistribution, modification, or commercial distribution without explicit permission from the owner is prohibited.
