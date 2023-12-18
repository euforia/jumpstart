# Jumpstart

Jumpstart is a versatile code template generator that allows you to kickstart your projects with ease. 
> [!IMPORTANT]
> Jumpstart is under active development to support different frameworks and languages, for updates please star (or watch) the repository.

## Development

### Build

Build for your local architecture

```
make releases/jumpstart
```
## Getting started

#### 1. Clone the Repository

```bash
git clone https://github.com/nurdsoft/jumpstart
```
#### 2. Build for Local Machine

Navigate to the cloned repository and build the tool for your machine using the following command:
```bash
make releases/jumpstart
```

#### 3. Set Up GitHub Personal Access Token
Create a GitHub personal access token and set it as a variable GITHUB_TOKEN in your terminal profile.
```bash
export GITHUB_TOKEN=<your_token>
```
#### 4. List available templates
You can list the available templates using the following command:
```bash
releases/jumpstart template list
```
#### 5. Generate Your Project
Run the following command to generate a project:
```bash
releases/jumpstart -t <template name> <project name>
```
This command will create a private GitHub repository with the name ```<project name>``` and the chosen template ```<template name>```. Navigate into your project directory using:
```bash
cd <project name>
```
Now you're ready to start coding! Make changes, commit them, and push to your GitHub repository.

### License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/nurdsoft/jumpstart/blob/main/LICENCE.md) file for details.

### Contributing
We welcome contributions! Follow these guidelines to contribute to Jumpstart:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Submit a pull request.

### Support
If you encounter any issues or have questions, feel free to [open an issue](https://github.com/nurdsoft/jumpstart/issues). We appreciate your feedback!


Happy coding with Jumpstart!
