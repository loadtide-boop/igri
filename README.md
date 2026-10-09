# igri

Signed game bundle for a private family TV app.

`app.json` holds the current version of the game. The TV app downloads it, checks its digital signature against the public key built into the app, and only then uses it. A file that is not signed with the matching private key is ignored.

This file is produced by a build script. Please do not edit it by hand.
