# How to Use

- All of the data for the newsletter can be typed into data.txt
- Once complete, double click the GENERATE.bat file and the code for the newsletter will be copied to your clipboard.

# Guide to data.txt
### FORMAT:
date \
heading \
information \
<> \
date \
heading \
information

- Each section should be separated by typing <>
- Dates are optional, but should be replaced with something like a dot instead of being left empty.

# SETUP
- Must have node.js installed
- Upon downloading from GitHub, run `npm i` in the project directory.
- MACOS ONLY:
  - run `chmod a+x GENERATE-mac`
- Change data.txt to have the required content, then run GENERATE-windows.bat or GENERATE-mac.bat depending on your operating system.