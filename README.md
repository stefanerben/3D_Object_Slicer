# Python-based Slicer from STL to PNG Images

## Introduction
This project is a Python-based slicer that generates PNG images from STL files. Currently in production but not yet complete, the code does not include any visualization or graphical user interface (GUI). All scaling and orientation settings must be configured beforehand. This codebase is an extension of a different [project](https://github.com/matthewelse/pySlice), which was developed to automate the creation of schematics for LEGO sculptures based on 3D models.

## Original Text by Matthew Else
A 3D model slicing algorithm, written by Matthew Else in Python. The primary motivation for developing this algorithm was the need for a Python-based solution and the desire to avoid using alternatives licensed under AGPL, which require the release of source code for commercial use.

## Supported File Formats
The code currently supports the following file format:
- STL

Future updates may include support for additional formats such as OBJ. However, for now, STL is sufficient. The current version cannot generate G-Code, but it can generate all layers through a simple for loop.

## Goals
The goal of this project is to provide a tool for generating schematics for LEGO sculptures based on 3D models. By automating the process of creating PNG images from STL files, I aim to streamline the workflow for designing and building LEGO sculptures.

## Limitations
Several limitations of this project should be noted:

1. **Visualization and GUI:** The code does not include any visualization or graphical user interface. All configurations must be done beforehand.
2. **File Format Support:** Currently, only STL files are supported. Future updates may include additional formats.
3. **G-Code Generation:** The code does not generate G-Code. This functionality may be added in future updates.

## Usage
To use this code, set the file paths and slicing heights in the parameterization section, and run the slicing algorithm. The PNG images will be saved in the specified output directory.

## License
This project is licensed under the MIT License.

---

I hope this project helps others in the future who are interested in generating PNG images from STL files for purposes such as creating schematics for LEGO sculptures.
