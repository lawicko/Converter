# Converter

This simple script will automatically create pdf assets from any svg assets your graphic designer commits to his design repository. Useful in the following scenario:

- you need assets in pdf format (for instance, iOS development as of 27 Feb 2015)
- your graphic designer ouputs everything to his design repository in svg format (shared resources between iOS and Android)

# Prerequisits

The script uses Inkscape app for OSX, so make sure you install it properly in the Applications folder before running the script.

# Installation

1. Clone the repo
2. Copy hook, rename to pre-commit and replace your designers' .git/hooks/pre-commit
3. Make sure to configure the script to your liking, specifically dirPrefix needs to be set to the folder you want to convert
