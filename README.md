mangos-zero script library
==========================
The *mangos-zero* script library based on [ScriptDev2][1] has been merged into
the [mangos-zero server][2] and thus you will *not* need to keep a clone of
this repository anymore.

If you upgrade to *mangos-zero* version **[0.18.1][3]** or newer, you should
first backup any changes you made to the script library, and remove your old
clone of this repository from the mangos-zero source tree.

Then update mangos-zero, and you will now have both the server and scripts in
one repository.

This eliminates the need for patching the server to include scripts, and also
allows us to easier upgrade scripts in the future.


[1]: https://github.com/scriptdev2/scriptdev2-classic "ScriptDev2 for vanilla WoW"
[2]: https://github.com/mangoszero/server "mangos-zero server"
[3]: https://github.com/mangoszero/server/releases/tag/v0.18.1
