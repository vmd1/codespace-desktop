# GitHub Codespace Desktop Template

This is a template repository for creating a GitHub Codespace with a desktop environment enabled.

## Overview

This template uses the `desktop-lite` feature to provide a lightweight desktop environment (XFCE) within your Codespace. This allows you to run graphical applications and development tools with a visual interface rather than just a command line.

## Features

- **Desktop Environment**: Desktop-lite XFCE environment running on port 6080
- **VNC Access**: Direct VNC connection on port 5901
- **Web Browser**: Access the desktop through the web interface
- **Development Ready**: Pre-configured for development workflows with a GUI

## Getting Started

1. **Create a Codespace** from this template
2. **Access the Desktop** by:
   - Opening the ports view in VS Code
   - Clicking on the forwarded port for port 6080
   - This will open the desktop interface in your browser

3. **Login to the Desktop**:
   - Default password: `vscode`

## Accessing the Desktop

### Via Web Browser
- The desktop-lite web interface is available on port 6080
- Simply forward port 6080 and click the open URL

### Via VNC Client
- VNC server runs on port 5901
- Use any VNC client to connect
- Password: `vscode`

## Use Cases

- Running GUI applications within your Codespace
- Testing desktop/GUI-based applications
- Development work that requires a graphical interface
- Remote development with visual feedback

## Next Steps

Start creating and customizing your development environment. You can install additional tools, packages, and applications as needed within the Codespace.
