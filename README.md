[![codebeat badge](https://codebeat.co/badges/520cc9b2-ac22-49ba-9fa1-8c53c4ff4052)](https://codebeat.co/projects/github-com-syky27-lunch_guy-ios)


# lunch_guy-ios (in progress)
A simple application for retrieving lunch menus of selected restaurants using https://github.com/tomaskadlec/lunch_guy API

## Screenshots

![1](https://raw.githubusercontent.com/syky27/lunch_guy-ios/dev/screenshots/2.png)


![2](https://raw.githubusercontent.com/syky27/lunch_guy-ios/dev/screenshots/1.png)

## Localization

The app is currently localized into Czech and English. We use `SwiftGen` to generate localization `enum`s which are used acrossed whole app. If you updated the `Localization.strings` files, just switch Xcode target to Localization and build it. While editing these files, remember to always edit all languages accordingly - but don't worry, Danger will check that for you once you create the pull request.
