# Flipper Zero app template

Assume the root of this repository is the root of an application folder.
> (Eg. If the repo is named `my-cool-app`, then it will exist as `applications/my-cool-app` within the flipperzero-firmware repo)

With the exceptions of:
- Dotiles (any file/folder name starting with a .) are ignored.
- The `assets` folder is overlaid on top of the firmware repo's asset folder.
- The `lib` folder is overlaid on top of the firmware repo's lib folder.

All other subfolders will stay in the application's root folder. A Flipper Application Manifest file must be present as `application.fam` in the root directory.
