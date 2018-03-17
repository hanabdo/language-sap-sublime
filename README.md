# language-sap-sublime

Sublime Text 3 syntax support for different SAP source files

Uses Sublime modern syntax definition [sublime-syntax](http://www.sublimetext.com/docs/3/syntax.html)

Please check the umbrella repo [`language-sap`](https://github.com/krasnobaev/language-sap/) since this repo receive updates based on syntax definitions for `atom`.

To start local developing copy repo to Sublime `User` folder, e.g.:

```bash
FROM=~/github/language-sap/language-sap-sublime
TO=~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
cp -a $FROM $TO/
```

cleanup:

```bash
rm -rf $TO/language-sap-sublime
```
