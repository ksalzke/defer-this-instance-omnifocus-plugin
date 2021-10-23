# About

This is an Omni Automation solitary plug-in for OmniFocus that duplicates a repeating task to modify its defer date without affecting future instances"

_Please note that all scripts on my GitHub account (or shared elsewhere) are works in progress. If you encounter any issues or have any suggestions please let me know--and do please make sure you backup your database before running scripts from an amateur on the internet!_

## Known issues

Refer to the 'issues' in this repo for known issues and planned changes/enhancements.

# Installation & Set-Up

1. Click on the green `Clone or download` button above to download a `.zip` file of the file in this GitHub repository.
2. Unzip the downloaded file.
3. Move the `.omnifocusjs` file to your OmniFocus plug-in library folder.

# Actions

## Defer This Instance

This action can be run on a single selected repeating task. It:

1. Makes a non-repeating copy of the selected task
2. Prompts the user for a new defer date and sets the date of the copy
3. Skips the current instance of the original task